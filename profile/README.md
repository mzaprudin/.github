<p align="center"><strong>English</strong> · <a href="https://github.com/mzaprudin/.github/blob/main/profile/README.RU.md">Русский</a></p>

<h1><img src="https://raw.githubusercontent.com/mzaprudin/.github/main/profile/assets/readme/hero-en.svg" width="100%" alt="Mikhail Zaprudin — Senior Software &amp; R&amp;D Engineer"></h1>

I am a software engineer and architect. I design **real-time systems and low-latency components** for high-frequency data streams and tackle research problems.

I independently handle the full development cycle: defining the problem, choosing the architecture, optimizing **CPU/GPU, memory and networking**, and setting up monitoring. My **AI-first** workflow uses LLMs and code generation for research, implementation and learning new languages and domains.

## Selected engineering work

Software components and experiments demonstrating specific engineering decisions, alongside hobby hardware and firmware work.

| Repository | Purpose, engineering and examples |
|---|---|
| **01** · [zero-alloc-json](https://github.com/mzaprudin/zero-alloc-json) | **Zero-allocation JSON processing** in C#/.NET: updates fill reusable objects and collections; serialization reuses the output buffer.<br>[Benchmarks](https://github.com/mzaprudin/zero-alloc-json#json-and-routing-benchmarks) · [Example](https://github.com/mzaprudin/zero-alloc-json/tree/main/samples/ZeroAlloc.Json.Demo) |
| **02** · [pipelines-websocket](https://github.com/mzaprudin/pipelines-websocket) | **Zero-allocation WebSocket receive design** over TCP/TLS and Pipelines. Handlers read unfragmented messages from pooled memory; CPU and allocations are measured over physical Ethernet.<br>[Ethernet measurements](https://github.com/mzaprudin/pipelines-websocket#websocket-over-physical-ethernet) · [Client examples](https://github.com/mzaprudin/pipelines-websocket/tree/main/samples/Pipelines.WebSockets.Demo) |
| **03** · [gpu-hyperparam-scheduler](https://github.com/mzaprudin/gpu-hyperparam-scheduler) | Time-series CNN–Transformer–BiLSTM training with weighted focal loss. **Resumable multi-GPU search** runs one asynchronous worker per GPU and retains trial history.<br>[CPU example and results](https://github.com/mzaprudin/gpu-hyperparam-scheduler/blob/main/examples/README.md) |
| **04** · [AirWireCom](https://github.com/mzaprudin/AirWireCom) | Wireless UART over ESP-NOW with button-selected roles, saved pairing and **baud synchronization**. The computer connects to the first ESP board via USB CDC or a USB–UART adapter to exchange data wirelessly with a device connected to the second board’s UART.<br>[Connection and pairing](https://github.com/mzaprudin/AirWireCom#how-it-works) |
| **05** · [DialScroll](https://github.com/mzaprudin/DialScroll) | Wireless scroll-wheel firmware for nRF52840 and MT6701: **circular angle filtering**, small-motion accumulation, adaptive polling and BLE HID output.<br>[Enclosure CAD and animation](https://github.com/mzaprudin/DialScroll#enclosure) |
| **06** · [RFIDHunter](https://github.com/mzaprudin/RFIDHunter) | Android item finder with an external Bluetooth UHF RFID reader: **signal-strength tag selection**, adaptive voice activity detection, offline Vosk recognition and a transactional backup queue.<br>[Mock-reader walkthrough](https://github.com/mzaprudin/RFIDHunter/blob/main/docs/DEVELOPMENT.md#mock-walkthrough) |
| **07** · [FilamentDryer](https://github.com/mzaprudin/FilamentDryer) | ESP32 filament-dryer firmware with **moisture-release estimation**, cascaded temperature control and pulse ventilation. Fans start before heating.<br>[PCB model and layouts](https://github.com/mzaprudin/FilamentDryer#pcb) |
| **08** · [notiprint](https://github.com/mzaprudin/notiprint) | Android notification printing over Bluetooth with a **persistent Room queue**, retries and recovery. Cyrillic text is rendered as ESC/POS bitmaps.<br>[Verification](https://github.com/mzaprudin/notiprint#verification) |
