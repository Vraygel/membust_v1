memboost/
├── index.html (SPA контейнер)
├── css/
│   ├── main.css (общие стили)
│   ├── auth.css
│   ├── dictionary.css
│   ├── training.css
│   └── components/
│       ├── header.css
│       ├── modal.css
│       └── word-card.css
├── js/
│   ├── app.js (инициализация SPA)
│   ├── router.js (маршрутизация)
│   ├── api.js (работа с API)
│   ├── models/ (классы данных)
│   │   ├── user.js
│   │   ├── dictionary.js
│   │   ├── word.js
│   │   └── training.js
│   ├── components/ (UI компоненты)
│   │   ├── header.js
│   │   ├── dictionary-list.js
│   │   ├── word-list.js
│   │   ├── modal.js
│   │   └── search.js
│   └── pages/ (страницы приложения)
│       ├── auth.js
│       ├── main.js
│       ├── training.js
│       └── select-words.js
└── utils/
    ├── helpers.js
    └── constants.js