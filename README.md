# SecondFlow Store - Статический сайт

Статический сайт для B2B маркетплейса неликвидов SecondFlow Store.

## Структура проекта
secondflow-static/
├── index.html
├── about.html
├── buyers.html
├── sellers.html
├── categories.html
├── prices.html
├── why.html
├── getting-started.html
├── faq.html
├── contacts.html
├── complaints.html
├── terms.html
├── privacy.html
├── offer.html
├── rules.html
├── assets/
│ ├── css/
│ │ └── main.css
│ ├── js/
│ │ └── main.js
│ └── images/
│ ├── seller-logo-white.jpeg
│ ├── store-logo-white.jpeg
│ ├── ecosystem-logo.png
│ ├── main.jpg
│ ├── about-0.jpg
│ ├── about-1.jpg
│ ├── about-2.jpg
│ ├── buyers.jpg
│ ├── sellers.jpg
│ ├── categories.jpg
│ ├── prices.jpg
│ ├── why.jpg
│ ├── why-3.jpg
│ ├── getting-started.jpg
│ ├── complaints.jpg
│ ├── rules.jpg
│ ├── qr-buyers.jpg
│ └── qr-sellers.jpg
└── README.md


## Особенности

- Полностью адаптивный дизайн
- Мобильное меню
- Анимации при прокрутке
- QR-коды для быстрого доступа к приложениям
- Все страницы имеют одинаковые header и footer
- SEO-оптимизированные заголовки

## Деплой на Vercel

1. Загрузите проект в GitHub репозиторий
2. Перейдите на [vercel.com](https://vercel.com)
3. Импортируйте репозиторий
4. Настройки деплоя:
   - Framework Preset: Static
   - Build Command: (оставить пустым)
   - Output Directory: (оставить пустым)
5. Нажмите Deploy

## Локальный запуск

Просто откройте `index.html` в браузере или используйте Live Server в VS Code.

## Технологии

- HTML5
- CSS3 (Flexbox, Grid)
- JavaScript (ES6+)
- Без зависимостей

## Контакты

- Email: info@secondflow.store
- Телефон: +79211050409
- Telegram: @SecondFlow

Инструкция по деплою:
Создайте все папки и файлы по указанной структуре

Загрузите изображения в папку assets/images/ (используйте предоставленные названия файлов)

Создайте GitHub репозиторий и загрузите все файлы

Деплой на Vercel:

Зайдите на vercel.com

Авторизуйтесь через GitHub

Нажмите "Add New" → "Project"

Выберите ваш репозиторий

Настройки деплоя:

Framework Preset: Other

Build Command: (оставить пустым)

Output Directory: (оставить пустым)

Нажмите "Deploy"

Сайт будет доступен по адресу типа https://secondflow.vercel.app

Важно: Все пути в HTML файлах указаны от корня (/assets/css/main.css), что корректно работает на Vercel. Для локального тестирования может потребоваться настроить базовый путь или использовать относительные пути.
