# Maximbit — Engineering Portfolio

Интерактивное портфолио разработчика: **Telegram-боты на Python (aiogram 3, Telethon)**, **Telegram Mini Apps** и **ремонт / стабилизация Python-кода**.

**Live Demo:**
- 🇷🇺 [Открыть портфолио (RU)](https://maxxximka55.github.io/maximbit-portfolio/)
- 🇬🇧 [Open Portfolio (EN)](https://maxxximka55.github.io/maximbit-portfolio/?lang=en)

---

## Интерактивные кейсы

Каждый кейс — отдельный самодостаточный HTML-артефакт без сборщиков и фреймворков. Всё кликабельно прямо в браузере и на телефоне.

| # | Кейс | Описание | Ссылка |
| :-: | :--- | :--- | :--- |
| **01** | **Telegram Mini App — Storefront** | Витрина магазина с темами Telegram (Light/Dark/Slate), корзиной, промокодами, валютами и live-тюнером CSS-токенов | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/tg-miniapp-store-prototype.html) |
| **02** | **Python Bugfix & Code Review** | Разбор стабилизации сломанного `aiogram`-бота после ИИ: Before/After Diff, фильтры критичности, Risk Map | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/python-bugfix-code-review.html) |
| **03** | **Production Bot Topology** | Интерактивная inline-SVG схема деплоя бота на Ubuntu VPS (Nginx, webhook, SQLite WAL, systemd, бэкапы) | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/bot-architecture-topology.html) |
| **04** | **Bot Orders & Logs Explorer** | Админ-консоль заказов: фасетные фильтры, живые KPI, почасовой SVG-график, инспектор JSON, экспорт CSV/JSON | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/bot-analytics-explorer.html) |
| **05** | **P2P Terminal Live Demo** | Интерфейс управления P2P-ботом в рамке телефона с локальной имитацией моста (тестовые данные) | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/p2p-terminal-live-demo.html) |
| **06** | **P2P Bot Database Schema** | Кликабельная ER-диаграмма БД бота с подсветкой связей и готовым SQLite DDL для каждой таблицы | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/p2p-bot-schema-erd.html) |
| **07** | **Telegram Payments Matrix** | Взвешенная матрица выбора оплаты (Telegram Stars, ЮKassa, CryptoBot) с ползунками весов и формулой | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/payments-comparison-matrix.html) |
| **08** | **Project Delivery Roadmap** | Интерактивная диаграмма Ганта с зависимостями этапов и живым пересчётом сроков от даты старта | [Открыть](https://maxxximka55.github.io/maximbit-portfolio/project-roadmap-timeline.html) |

---

## Особенности реализации

- **Стек портфолио:** чистый HTML5, CSS3 (CSS-переменные, `@media print`, адаптив под мобильные) и Vanilla JS без внешних библиотек и этапа сборки.
- **Двуязычность (`RU | EN`):** встроенный переключатель на каждой странице с синхронизацией языка через параметр `?lang=en`.
- **Графика:** все диаграммы, схемы и графики собраны на inline `<svg>` с выделяемым текстом.
- **Калькулятор задач:** на главной странице доступен интерактивный расчёт стоимости и сроков с копированием готового брифа.

## Локальный запуск

Склонируйте репозиторий и откройте `index.html` в любом браузере. Для корректной работы **Case 05** файлы `p2p-terminal-live-demo.html` и `terminal-demo.html` должны находиться в одной директории.
