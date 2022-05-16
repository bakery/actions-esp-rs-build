# ESP32 RS Project build

Usage:

```yml
- uses: "bakery/actions-esp-rs-build@v1.0.0"
  with:
    command: export RUST_ESP32_STD_DEMO_WIFI_SSID=ssid; export RUST_ESP32_STD_DEMO_WIFI_PASS=pass; cargo +esp build
```
