Интернет-магазин с карточками товаров
Этот проект представляет собой интернет-магазин с карточками товаров, разработанный с использованием современных инструментов и технологий. Проект включает в себя базовую структуру приложения, управление состоянием с помощью Redux Toolkit, а также различные функции, такие как фильтрация, сортировка, поиск товаров, корзина и поддержка темной/светлой темы.

Технологии
React 18+: Библиотека для построения пользовательских интерфейсов.

Redux Toolkit: Управление состоянием приложения.

Material-UI (MUI): Библиотека компонентов для создания современного и адаптивного интерфейса.

Vite: Сборщик проекта, обеспечивающий высокую производительность и удобство разработки.

Mock API: Используется для имитации API товаров.

Функциональность
Отображение товаров: Базовый интерфейс для отображения карточек товаров.

Фильтрация, сортировка и поиск: Возможность фильтрации, сортировки и поиска товаров.

Корзина: Добавление и удаление товаров, отображение общей стоимости.

Локальное кэширование корзины: Сохранение состояния корзины в локальном хранилище браузера.

Темы: Переключение между светлой и темной темой с сохранением состояния.

Установка и запуск
Клонирование репозитория:
git clone https://github.com/ваш-username/интернет-магазин.git
cd интернет-магазин

Установка зависимостей:
npm install

Запуск сервера для товаров:
json-server --watch public/data.json --port 3001

Запуск проекта:
npm run dev
