# Crypto-rabbit

Делаю практические проекты на Python, Telegram, AI-интеграциях, автоматизации и веб-разработке. В репозиториях больше всего видно работу с ботами, API, хранением данных, крипто-инструментами и небольшими продуктами, которые можно запустить и проверить.

## Навыки по проектам

**Python и backend**

- Telegram-боты и обработка пользовательских сценариев.
- FastAPI, WebSocket, фоновые процессы и запуск сервисов.
- Интеграции с внешними API: Bybit, Telegram, OpenAI.
- Скрипты запуска, настройка окружения, работа с зависимостями.

**AI и автоматизация**

- AI-помощники для Telegram с понятной логикой поведения.
- OpenAI API для анализа, рекомендаций и обработки пользовательских данных.
- Google Apps Script и Google Sheets как serverless backend и база для MVP.
- Ограничение токенов, хранение краткого контекста, правила безопасности для ответов.

**Crypto / trading / TON**

- Сигнальный бот для Bybit Futures на основе пересечений moving averages.
- Мониторинг торговых пар и передача сигналов через backend-интерфейс.
- TON/NFT workspace: assets, metadata, contracts, Node.js и scripts для проверки структуры.

**Web и инфраструктура**

- PHP-сайты, архивы сайтов и восстановление проектов с хостинга.
- Docker basics, PowerShell scripts, локальная настройка окружения.
- README, deployment docs, quick-start инструкции и техническая документация.

**Игровые переводчики**

- Отдельные окна перевода поверх игры без изменения файлов клиента и без чтения памяти игры.
- Локальное распознавание английского текста через OCR Windows.
- Онлайн-перевод нового текста и сохранение результатов в SQLite для повторного использования.

## Проекты

| Проект | Что внутри | Стек |
| --- | --- | --- |
| [mtga-russian-helper](https://github.com/Crypto-rabbit/mtga-russian-helper) | Русский помощник для MTG Arena. Распознаёт карту через OCR Windows, ищет её через Scryfall, показывает официальный русский текст или делает онлайн-перевод. Карты и выпуски сохраняются в локальной SQLite-базе, поэтому найденная карта повторно открывается без сетевого запроса. Работает отдельным окном поверх игры и завершается вместе с MTG Arena. | PowerShell, Python, SQLite, Windows OCR, Scryfall API |
| [lu4-russian-helper](https://github.com/Crypto-rabbit/lu4-russian-helper) | Фоновый переводчик для Lineage/LU4. Распознаёт диалоги, задания и интерфейс рядом с курсором, переводит новый текст через интернет и сохраняет его в SQLite по категориям. Показывает перевод поверх игры, поддерживает длинный текст и автоматически закрывается после выхода из игры. | PowerShell, Python, SQLite, Windows OCR |
| [avito-card-parser](https://github.com/Crypto-rabbit/avito-card-parser) | Сбор открытых данных объявлений Avito без запуска тяжёлого браузера для каждой карточки, сохранение прогресса и выгрузка в CSV, JSON или Google Sheets | Python, HTTP, HTML parsing, Google Sheets |
| [bybit-ma-signal-bot](https://github.com/Crypto-rabbit/bybit-ma-signal-bot) | Сигнальный бот для Bybit Futures, MA-сигналы, мониторинг пар, FastAPI/WebSocket | Python, FastAPI, WebSocket |
| [Bitget MA bot](https://github.com/Crypto-rabbit/-----------) | Сбор рыночных данных Bitget и работа с сигналами на основе скользящих средних | Python, Bitget API |
| [monast](https://github.com/Crypto-rabbit/monast) | PHP-сайт по монастырю, архив и восстановление веб-проекта с хостинга | PHP |
| `helen-sport-` | Приватный Telegram AI health coach: питание, вода, сон, тренировки, onboarding, storage, deployment docs | JavaScript, Google Apps Script, Google Sheets, OpenAI, Python |
| `TelegramNFT` | Локальная рабочая область для TON/NFT: assets, metadata, contracts и validation scripts | Node.js, TON |

## Сейчас развиваю

- Telegram-ботов и AI-агентов, которые работают не только как чат, а как полезный инструмент.
- Автоматизацию через Python, Google Apps Script и локальные скрипты.
- Крипто-инструменты: сигналы, аналитика, TON/NFT-структуры.
- Переход от MVP к более надежной архитектуре: хранение данных, деплой, документация, проверки.

## Контакты

GitHub: [Crypto-rabbit](https://github.com/Crypto-rabbit)
