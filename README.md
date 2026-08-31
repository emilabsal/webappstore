# 🛒 WebAppStore

Веб-приложение для демонстрации и управления каталогом товаров интернет-магазина.

## 🚀 Технологический стек

| Технология | Назначение |
|------------|------------|
| **Vue 3** | Основной фреймворк |
| **Vite** | Сборщик и dev-сервер |
| **JavaScript (ES6+)** | Язык программирования |
| **CSS** | Стилизация компонентов |
| **HTML5** | Разметка страниц |

## 📦 Установка и запуск

### Требования
- Node.js ≥ 18
- npm ≥ 9

### Установка зависимостей
```bash
npm install
```

### Запуск в режиме разработки
```bash
npm run dev
```

### Сборка для продакшена
```bash
npm run build
```

### Предпросмотр продакшен-сборки
```bash
npm run preview
```

## 💻 Примеры использования

### Запуск dev-сервера
```bash
npm run dev
# Сервер запустится на http://localhost:5173
```

### Сборка проекта
```bash
npm run build
# Результат появится в папке dist/
```

## 📁 Структура проекта

```
webappstore/
├── 📄 index.html              # Главный HTML-файл
├── 📄 package.json            # Конфигурация npm
├── 📄 vite.config.js          # Конфигурация Vite
├── 📁 public/                 # Статические файлы
│   └── 📄 vite.svg
├── 📁 src/                    # Исходный код
│   ├── 📄 App.vue             # Корневой компонент
│   ├── 📄 main.js             # Точка входа
│   ├── 📄 style.css           # Глобальные стили
│   ├── 📁 assets/             # Ресурсы
│   │   └── 📄 vue.svg
│   └── 📁 components/         # Vue-компоненты
│       └── 📄 HelloWorld.vue
└── 📁 dist/                   # Продакшен-сборка
    ├── 📄 index.html
    └── 📁 assets/             # Собранные ассеты
```

## 📄 Лицензия

MIT License

Copyright (c) 2024 WebAppStore

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.