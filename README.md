# Мария Чепурова — Сайт-портфолио

Минималистичный editorial-сайт для фотографа в стиле чёрно-белого журнального дизайна.

## Структура проекта

```
maria_chepurova/
├── index.html              ← Главная страница
│
├── css/
│   ├── reset.css           ← Сброс стилей (box-model)
│   ├── variables.css       ← Дизайн-токены (цвета, шрифты, отступы)
│   ├── base.css            ← Глобальные стили, футер
│   ├── nav.css             ← Навигация
│   ├── hero.css            ← Главный экран (hero)
│   ├── about.css           ← Раздел "Обо мне"
│   ├── portfolio.css       ← Раздел "Портфолио" (асимметричная сетка)
│   ├── works.css           ← Раздел "Мои работы"
│   ├── contact.css         ← Раздел "Контакты"
│   ├── animations.css      ← Scroll-reveal анимации
│   └── responsive.css      ← Адаптивность (mobile / tablet)
│
├── js/
│   └── reveal.js           ← Intersection Observer для анимаций
│
└── assets/
    └── images/             ← Папка для фотографий
        └── (сюда добавить фото)
```

## Как добавить фотографии

### Hero (главный экран)
Замените `<div class="hero-photo-placeholder">` на:
```html
<img class="hero-photo" src="assets/images/hero.jpg" alt="Мария Чепурова">
```

### Портфолио и работы
Замените `<div class="img-placeholder"></div>` на:
```html
<img src="assets/images/portfolio-1.jpg" alt="Индивидуальная съёмка"
     style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
```

## Контакты и ссылки

Найдите и замените в `index.html`:
- `mailto:maria@chepurova.ru` → реальный email
- `href="#"` у кнопки Instagram/Telegram → реальные ссылки
- `@mariachepurova` в nav → реальный хэндл
- `Фотограф · Москва` в футере → реальный город

## Технологии

- Чистый HTML5 / CSS3 / vanilla JS
- Шрифты: Playfair Display + Inter (Google Fonts)
- Без фреймворков, без сборщиков — открывается напрямую в браузере
