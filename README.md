Вики фандома 'Мир Звёздного пути'
Это шаблон для сайта фандома в стиле вики, размещённого на GitHub Pages. Сайт использует Markdown (через Jekyll), CSS и JavaScript для создания адаптивного, SEO-оптимизированного сайта с переключением тем (светлая/тёмная).
Структура проекта
fandom-wiki/
├── _layouts/
│   └── default.html       # Основной шаблон страницы
├── _includes/
│   ├── header.html        # Хедер
│   ├── nav.html           # Навигация
│   └── footer.html        # Футер
├── index.md              # Главная страница
├── characters.md         # Страница персонажей
├── world.md              # Страница мира
├── history.md            # Страница истории
├── gallery.md            # Страница галереи
├── about.md              # Страница о проекте
├── css/
│   └── styles.css        # Стили
├── js/
│   └── script.js         # Скрипты (переключение тем, мобильная навигация)
├── images/
│   ├── placeholder1.jpg
│   ├── placeholder2.jpg
│   └── placeholder3.jpg
├── _config.yml           # Конфигурация Jekyll
└── README.md             # Этот файл

Установка и запуск

Создайте репозиторий на GitHub:

Для пользовательского сайта: назовите репозиторий username.github.io (замените username на ваше имя пользователя).
Для проекта: любое имя, например, fandom-wiki.
Сделайте репозиторий публичным для бесплатного плана.


Загрузите файлы:

Склонируйте репозиторий: git clone https://github.com/username/fandom-wiki.git
Скопируйте файлы из этого шаблона в репозиторий.
Зафиксируйте и отправьте изменения: git add . && git commit -m "Initial commit" && git push origin main


Настройте GitHub Pages:

Перейдите в репозитории в Settings > Pages.
Выберите ветку main и папку / (root).
Сохраните. Сайт будет доступен через 1–5 минут по адресу https://username.github.io или https://username.github.io/fandom-wiki.


Настройка Jekyll:

Убедитесь, что _config.yml настроен (проверьте baseurl и url).
GitHub Pages автоматически использует Jekyll для обработки .md файлов.



Добавление контента

Markdown страницы: Редактируйте index.md, characters.md, world.md, history.md, gallery.md, about.md. Добавляйте новые .md файлы с фронт-маттером:---
layout: default
title: Название страницы
description: Описание для SEO
keywords: ключевые, слова
---


Изображения: Поместите в папку images/ и используйте пути вида /fandom-wiki/images/filename.jpg.
Навигация: Обновите _includes/nav.html для новых страниц.

Настройка Disqus (опционально)

Раскомментируйте код Disqus в index.md.
Зарегистрируйтесь на Disqus и получите shortname.
Замените your-disqus-shortname на ваш shortname.

Кастомизация

Темы: Измените переменные в css/styles.css (например, --primary-color).
Навигация: Обновите _includes/nav.html для новых пунктов.
SEO: Обновите фронт-маттер в .md файлах.

Устранение неисправностей

Сайт не отображается? Проверьте Settings > Pages и логи в Actions.
Ошибки Jekyll? Убедитесь, что фронт-маттер корректен.
Проблемы с изображениями? Проверьте пути в images/.

Лицензия
© 2025 Фандом 'Мир Звёздного пути'. Используйте и модифицируйте по своему усмотрению.