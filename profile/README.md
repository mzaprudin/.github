# Firmware, data processing and machine learning

English · [Русский](https://github.com/mzaprudin/.github/blob/main/profile/README.RU.md)

I build firmware and software that turn sensor readings into usable data, from embedded control and wireless links to signal processing, model training and applications.

## Projects

| Project | Purpose and engineering |
|---|---|
| [DialScroll](https://github.com/mzaprudin/DialScroll) | Wireless scroll-wheel firmware on nRF52840 and MT6701, with circular filtering, small-movement accumulation, adaptive polling and BLE HID output. |
| [gpu-hyperparam-scheduler](https://github.com/mzaprudin/gpu-hyperparam-scheduler) | Trains time-series CNN–Transformer–BiLSTM models with weighted focal loss; asynchronous search uses one worker per GPU and resumes saved trial history. |
| [RFIDHunter](https://github.com/mzaprudin/RFIDHunter) | Android item finder for IH25: signal-strength tag selection, adaptive voice activity detection, offline Vosk recognition and a transactional backup queue. |
| [FilamentDryer](https://github.com/mzaprudin/FilamentDryer) | ESP32 filament-dryer firmware estimates moisture release from humidity, uses cascaded temperature control and pulse ventilation, and enables fans before heating. |
| [zero-alloc-json-ws](https://github.com/mzaprudin/zero-alloc-json-ws) | C#/.NET library fills reusable objects from JSON, compiles writes, routes UTF-8 directly and receives WebSocket messages in pooled memory; JSON and physical Ethernet benchmarks. |
| [AirWireCom](https://github.com/mzaprudin/AirWireCom) | ESP-NOW serial bridge for ESP32/ESP8266: shared pairing firmware, persistent peer settings and synchronized baud rates across a wireless USB-to-UART link. |
| [notiprint](https://github.com/mzaprudin/notiprint) | Android notification printer with a durable Room queue, retries and recovery after failures; Cyrillic text is rendered as ESC/POS bitmaps for Bluetooth printing. |

## Examples and measurements

- [CPU training example and recorded results](https://github.com/mzaprudin/gpu-hyperparam-scheduler/blob/main/examples/README.md)
- [RFID mock walkthrough](https://github.com/mzaprudin/RFIDHunter/blob/main/docs/DEVELOPMENT.md#mock-walkthrough)
- [JSON and routing benchmarks](https://github.com/mzaprudin/zero-alloc-json-ws#json-and-routing-benchmarks)
- [WebSocket measurements over physical Ethernet](https://github.com/mzaprudin/zero-alloc-json-ws#websocket-over-physical-ethernet)
