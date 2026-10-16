# Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание

Проект представляет собой учебную версию сайта интернет-магазина или каталога товаров, разработанную с использованием Bootstrap.

---

## Практическая работа 9

Выполнена главная страница на Bootstrap-сетке.

Реализовано:

- подключение Bootstrap через CDN;
- подключение `css/custom.css`;
- шапка страницы;
- Bootstrap-навигация;
- hero-блок на сетке;
- блок преимуществ;
- сетка популярных товаров;
- подвал страницы.

### Используемые технологии

- HTML;
- Bootstrap;
- CSS;
- Git;
- GitHub.

### Структура проекта

```text
kr2-bootstrap-shop/
├── index.html
├── css/
│   └── custom.css
├── README.md
└── .gitignore
```

### Этап 14. Коммит изменений

Проверьте состояние проекта:

```bash
git status
```

---

## Практическая работа 10

Тема: «Страница на Bootstrap: компоненты».

Выполнено:

- добавлена единая Bootstrap-навигация;
- создана страница каталога `catalog.html`;
- создана страница товара `product.html`;
- создана страница заявки `order.html`;
- использованы компоненты `navbar`, `card`, `btn`, `badge`, `alert`, `modal`, `form-control`, `input-group`, `form-check`, `accordion`;
- добавлен файл `css/custom.css` для минимальных доработок;
- проект подготовлен к сдаче контрольной работы №2.

### Структура проекта

- `index.html` — главная страница;
- `catalog.html` — каталог товаров;
- `product.html` — страница товара;
- `order.html` — форма заявки;
- `css/custom.css` — дополнительные стили проекта;
- `images/` — изображения проекта;
- `README.md` — описание проекта.

---

## Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

### Используемый фреймворк

Bootstrap.

### Способ подключения

Bootstrap подключён локально из папки `vendor/bootstrap/`.

### Реализованные компоненты Bootstrap

#### Навигация и лейаут

- navbar (с navbar-toggler и collapse)
- dropdown
- breadcrumb
- container / row / col-*
- d-flex, flex-column, min-vh-100, flex-grow-1

#### Контент

- card
- carousel (со стрелками управления)
- accordion
- table / table-striped / table-responsive
- badge

#### Формы

- form-control
- form-select
- form-label
- form-check
- modal (форма быстрой заявки)
- alert (успешная отправка)

#### Кнопки и утилиты

- btn (primary, outline-primary, outline-secondary, lg, sm, w-100)
- img-fluid, rounded, shadow-sm
- position-absolute, top-0, end-0, z-1
- bg-*, text-*, opacity-75
- visually-hidden, text-decoration-none
- mt-auto, w-100, h-100

#### JavaScript (data-атрибуты)

- data-bs-toggle="collapse" / "dropdown" / "modal"
- data-bs-dismiss="modal"
- data-bs-ride="carousel" / data-bs-slide

#### Собственный JS

- Обработка формы заявки (orderForm) с показом alert-success
- Обработка формы отзыва (reviewForm) с показом alert-success