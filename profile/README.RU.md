# Прошивки, обработка данных и машинное обучение

[English](https://github.com/mzaprudin/.github/blob/main/profile/README.md) · Русский

Я разрабатываю прошивки и программы, которые превращают показания датчиков в полезные данные: от управления устройствами и беспроводной передачи до обработки сигналов, обучения моделей и создания приложений.

## Проекты

| Проект | Назначение и инженерные решения |
|---|---|
| [DialScroll](https://github.com/mzaprudin/DialScroll) | Прошивка беспроводного колеса прокрутки на nRF52840 и MT6701: круговая фильтрация, накопление малых движений, адаптивный опрос и передача через BLE HID. |
| [gpu-hyperparam-scheduler](https://github.com/mzaprudin/gpu-hyperparam-scheduler) | Обучение CNN–Transformer–BiLSTM на временных рядах со взвешенной focal loss; асинхронный поиск использует один процесс на GPU и продолжает сохранённую историю запусков. |
| [RFIDHunter](https://github.com/mzaprudin/RFIDHunter) | Android-приложение для поиска вещей через отдельный UHF RFID-считыватель по Bluetooth: выбор метки по силе сигнала, адаптивное определение речи, офлайн-распознавание Vosk и транзакционная очередь резервного копирования. |
| [FilamentDryer](https://github.com/mzaprudin/FilamentDryer) | Прошивка сушилки филамента на ESP32: оценка выделения влаги по влажности воздуха, каскадное управление температурой, импульсная вентиляция и включение вентиляторов перед нагревом. |
| [zero-alloc-json-ws](https://github.com/mzaprudin/zero-alloc-json-ws) | Библиотека C#/.NET: заполнение готовых объектов данными из JSON, компилируемая запись, маршрутизация прямо из UTF-8 и приём WebSocket-сообщений в буферы из пула; бенчмарки JSON и физического Ethernet. |
| [AirWireCom](https://github.com/mzaprudin/AirWireCom) | Последовательный мост ESP-NOW для ESP32/ESP8266: общая прошивка сопряжения, сохранение параметров пары и синхронизация скорости в беспроводном канале USB–UART. |
| [notiprint](https://github.com/mzaprudin/notiprint) | Печать Android-уведомлений: сохраняемая очередь Room, повторные попытки и восстановление заданий после сбоев; кириллица в растровом ESC/POS по Bluetooth. |

## Примеры и измерения

- [Обучение на CPU и полученные результаты](https://github.com/mzaprudin/gpu-hyperparam-scheduler/blob/main/examples/README.RU.md)
- [Прохождение RFID-сценариев с mock-ридером](https://github.com/mzaprudin/RFIDHunter/blob/main/docs/DEVELOPMENT.RU.md#маршрут-mock)
- [Бенчмарки JSON и маршрутизации](https://github.com/mzaprudin/zero-alloc-json-ws/blob/main/README.ru.md#бенчмарки-json-и-маршрутизации)
- [Измерения WebSocket по физической сети Ethernet](https://github.com/mzaprudin/zero-alloc-json-ws/blob/main/README.ru.md#websocket-по-физической-сети-ethernet)
