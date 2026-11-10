# Firmware, data processing and machine learning

English · [Русский](https://github.com/mzaprudin/.github/blob/main/profile/README.RU.md)

I build firmware and software for measurement, continuous data processing and model training. The projects cover embedded control, wireless links, Android applications and .NET components that reuse memory.

## Projects

| Project | Purpose and engineering |
|---|---|
| [DialScroll](https://github.com/mzaprudin/DialScroll) | Wireless scroll-wheel firmware on nRF52840 and MT6701, with **circular angle filtering**, small-movement accumulation, adaptive polling and BLE HID output. |
| [gpu-hyperparam-scheduler](https://github.com/mzaprudin/gpu-hyperparam-scheduler) | Trains time-series CNN–Transformer–BiLSTM models with weighted focal loss; **resumable multi-GPU search** runs asynchronous workers, one per GPU, and retains trial history. |
| [RFIDHunter](https://github.com/mzaprudin/RFIDHunter) | Android item finder using an external Bluetooth UHF RFID reader: **signal-strength tag selection**, adaptive voice activity detection, offline Vosk recognition and a transactional backup queue. |
| [FilamentDryer](https://github.com/mzaprudin/FilamentDryer) | ESP32 filament-dryer firmware **estimates moisture release** from humidity, uses cascaded temperature control and pulse ventilation, and enables fans before heating. |
| [zero-alloc-json](https://github.com/mzaprudin/zero-alloc-json) | **Zero-allocation JSON processing** in C#/.NET: incoming updates fill prepared objects and collections; serialization reuses the output buffer. |
| [pipelines-websocket](https://github.com/mzaprudin/pipelines-websocket) | **Zero-allocation WebSocket design** over TCP/TLS and Pipelines: handlers read unfragmented messages directly from pooled memory; receiver CPU and allocations are measured over Ethernet. |
| [AirWireCom](https://github.com/mzaprudin/AirWireCom) | ESP-NOW serial bridge for ESP32/ESP8266: shared pairing firmware, persistent peer settings and **synchronized baud rates** across a wireless USB-to-UART link. |
| [notiprint](https://github.com/mzaprudin/notiprint) | Android notification printer with a **durable Room queue**, retries and recovery after failures; Cyrillic text is rendered as ESC/POS bitmaps for Bluetooth printing. |

## Examples and measurements

- [CPU training example and recorded results](https://github.com/mzaprudin/gpu-hyperparam-scheduler/blob/main/examples/README.md)
- [RFID mock walkthrough](https://github.com/mzaprudin/RFIDHunter/blob/main/docs/DEVELOPMENT.md#mock-walkthrough)
- [JSON and routing benchmarks](https://github.com/mzaprudin/zero-alloc-json#json-and-routing-benchmarks)
- [WebSocket measurements over physical Ethernet](https://github.com/mzaprudin/pipelines-websocket#websocket-over-physical-ethernet)
- [JSON parsing and writing example](https://github.com/mzaprudin/zero-alloc-json/tree/main/samples/ZeroAlloc.Json.Demo)
- [Both WebSocket clients example](https://github.com/mzaprudin/pipelines-websocket/tree/main/samples/Pipelines.WebSockets.Demo)
