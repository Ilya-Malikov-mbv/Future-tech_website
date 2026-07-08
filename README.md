# 🌐 FutureTech

Современный адаптивный многостраничный сайт, разработанный на **HTML5**, **SCSS** и **Vanilla JavaScript** без использования frontend-фреймворков.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)

---

## 📖 О проекте

Проект представляет собой полноценный многостраничный сайт цифрового агентства с современным интерфейсом, адаптивной версткой и собственными переиспользуемыми JavaScript-компонентами.

Основная цель проекта — практика создания сложной верстки, организации архитектуры проекта и разработки интерактивных UI-компонентов без использования React, Vue или других frontend-фреймворков.

---

## ✨ Возможности

- 📱 Адаптивная верстка
- 📄 Многостраничный сайт
- 🍔 Адаптивное мобильное меню
- 🎞 Кастомный видеоплеер
- 📑 Компонент Tabs
- 📋 Кастомный Select
- 📖 Expandable Content ("Показать ещё")
- ☎ Маска ввода телефона
- ♿ Поддержка клавиатурной навигации
- 🎨 SCSS с модульной структурой
- 🧩 Компонентная архитектура JavaScript

---

## 📄 Страницы

- Home
- News
- Blog
- Podcasts
- Resources
- Contacts

---

## 🛠️ Используемые технологии

### Frontend

- HTML5
- SCSS (Sass)
- JavaScript (ES6 Modules)

### Дополнительно

- Web Animations API
- IMask.js
- CSS Grid
- Flexbox
- BEM

---

## 📂 Структура проекта

```text
.
├── index.html
├── news.html
├── blog.html
├── podcasts.html
├── resources.html
├── contacts.html
│
├── styles/
│   ├── blocks/
│   ├── helpers/
│   ├── main.scss
│   └── main.css
│
├── scripts/
│   ├── BaseComponent.js
│   ├── ExpandableContent.js
│   ├── Header.js
│   ├── InputMask.js
│   ├── MatchMedia.js
│   ├── Select.js
│   ├── Tabs.js
│   ├── VideoPlayer.js
│   ├── main.js
│   └── utils/
│       └── pxToRem.js
│
├── images/
├── icons/
├── fonts/
├── videos/
│
├── package.json
└── README.md
```

---

## ⚙️ JavaScript-компоненты

### Header

- адаптивное бургер-меню;
- блокировка прокрутки страницы.

### Tabs

Переиспользуемый компонент вкладок с динамическим переключением контента.

### Select

Собственный компонент выпадающего списка.

Возможности:

- управление клавиатурой;
- поддержка ARIA;
- автоматическое позиционирование;
- синхронизация с нативным `<select>`;
- адаптация под мобильные устройства.

### ExpandableContent

Компонент плавного раскрытия контента с использованием Web Animations API.

### VideoPlayer

Кастомный видеоплеер с собственной панелью управления.

### InputMask

Маскирование телефонных номеров с помощью IMask.

### BaseComponent

Базовый абстрактный класс для реализации компонентов с управлением состоянием через Proxy.

---

## 🏗️ Архитектура

Проект построен по компонентному принципу.

Каждый UI-компонент:

- инкапсулирует собственную логику;
- самостоятельно подписывается на события;
- не зависит от остальных компонентов;
- может использоваться повторно на различных страницах сайта.

---

## 🚀 Запуск проекта

```bash
git clone https://github.com/<username>/<repository>.git
```

```bash
npm install
```

```bash
npm run sass-watch
```

После компиляции SCSS откройте `index.html` в браузере.

---

## 📚 Что было реализовано

- адаптивная многостраничная верстка;
- компонентная архитектура;
- собственные UI-компоненты;
- управление состоянием через Proxy;
- модульная организация JavaScript;
- модульная архитектура SCSS;
- работа с DOM API;
- Web Animations API;
- keyboard accessibility.

---

## 📌 Возможные улучшения

- переключение темы;
- сборка через Vite;
- unit-тестирование компонентов.

---

## 📄 Лицензия

Проект создан в образовательных целях и используется в качестве портфолио.
