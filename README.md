# PulseCore™ Shared Engine CDN (VietSites & SYNAPTIQ Lab)

Централизованный CDN-репозиторий технологических ядер платформы **VietSites & SYNAPTIQ Lab**.

```
https://synaptiqlab.github.io/engine/
├── salon/
│   ├── salon-engine.css        # Таблица стилей Salon Engine (App Layout 100dvh, Safe Areas, темы)
│   └── salon-engine.js         # Бандл Salon Engine (CRM, коллизии, D1 Cloud Sync, таймлайн)
├── space/
│   ├── space-engine.css        # Стили Space Engine (шахматка мест, переговорные, тарифы)
│   └── space-engine.js         # Бандл Space Engine (почасовая тарификация, резиденты)
└── shop/
    ├── shop-engine.css         # Стили Shop Engine (витрина-каталог, корзина, фильтры)
    └── shop-engine.js          # Бандл Shop Engine (заказы, склад, Telegram-бот)
```

## Использование в клиентских оболочках (Thin Shell):
```html
<link rel="stylesheet" href="https://synaptiqlab.github.io/engine/salon/salon-engine.css?v=20261106_core_v10">
<script src="https://synaptiqlab.github.io/engine/salon/salon-engine.js?v=20261106_core_v10"></script>
```
