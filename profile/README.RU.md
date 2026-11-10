# Прошивки, обработка данных и машинное обучение

[English](https://github.com/mzaprudin/.github/blob/main/profile/README.md) · Русский

Я разрабатываю прошивки и программы для измерений, непрерывной обработки данных и обучения моделей. В проектах — управление устройствами, беспроводная передача, Android-приложения и компоненты .NET с переиспользованием памяти.

## Проекты

| Проект | Назначение и инженерные решения |
|---|---|
| [DialScroll](https://github.com/mzaprudin/DialScroll) | Прошивка беспроводного колеса прокрутки на nRF52840 и MT6701: **круговая фильтрация**, накопление малых движений, адаптивный опрос и передача через BLE HID. |
| [gpu-hyperparam-scheduler](https://github.com/mzaprudin/gpu-hyperparam-scheduler) | Обучение CNN–Transformer–BiLSTM на временных рядах со взвешенной focal loss; **возобновляемый поиск на нескольких GPU** запускает асинхронные процессы по одному на видеокарту и сохраняет историю запусков. |
| [RFIDHunter](https://github.com/mzaprudin/RFIDHunter) | Android-приложение для поиска вещей через отдельный UHF RFID-считыватель по Bluetooth: **выбор метки по силе сигнала**, адаптивное определение речи, офлайн-распознавание Vosk и транзакционная очередь резервного копирования. |
| [FilamentDryer](https://github.com/mzaprudin/FilamentDryer) | Прошивка сушилки филамента на ESP32: **оценка выделения влаги** по влажности воздуха, каскадное управление температурой, импульсная вентиляция и включение вентиляторов перед нагревом. |
| [zero-alloc-json](https://github.com/mzaprudin/zero-alloc-json) | **Zero-allocation обработка JSON** на C#/.NET: входящие обновления заполняют готовые объекты и коллекции, запись переиспользует выходной буфер. |
| [pipelines-websocket](https://github.com/mzaprudin/pipelines-websocket) | **Zero-allocation подход в WebSocket** на TCP/TLS и Pipelines: обработчик читает нефрагментированные сообщения прямо из памяти пула; CPU и аллокации измерены по Ethernet. |
| [AirWireCom](https://github.com/mzaprudin/AirWireCom) | Последовательный мост ESP-NOW для ESP32/ESP8266: общая прошивка сопряжения, сохранение параметров пары и **синхронизация скорости** в беспроводном канале USB–UART. |
| [notiprint](https://github.com/mzaprudin/notiprint) | Печать Android-уведомлений: **сохраняемая очередь Room**, повторные попытки и восстановление заданий после сбоев; кириллица в растровом ESC/POS по Bluetooth. |

## Примеры и измерения

- [Обучение на CPU и полученные результаты](https://github.com/mzaprudin/gpu-hyperparam-scheduler/blob/main/examples/README.RU.md)
- [Прохождение RFID-сценариев с mock-ридером](https://github.com/mzaprudin/RFIDHunter/blob/main/docs/DEVELOPMENT.RU.md#маршрут-mock)
- [Бенчмарки JSON и маршрутизации](https://github.com/mzaprudin/zero-alloc-json/blob/main/README.ru.md#бенчмарки-json-и-маршрутизации)
- [Измерения WebSocket по физической сети Ethernet](https://github.com/mzaprudin/pipelines-websocket/blob/main/README.ru.md#websocket-по-физической-сети-ethernet)
- [Пример разбора и записи JSON](https://github.com/mzaprudin/zero-alloc-json/tree/main/samples/ZeroAlloc.Json.Demo)
- [Пример обоих WebSocket-клиентов](https://github.com/mzaprudin/pipelines-websocket/tree/main/samples/Pipelines.WebSockets.Demo)
