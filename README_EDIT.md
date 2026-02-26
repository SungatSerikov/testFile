# 🌟 Сайт социальных контактов

## Готовый к запуску проект!

Это современный одностраничный веб-сайт (landing page) для отображения ваших социальных сетей и контактов.

---

## 📋 Как редактировать данные

### 1. **Основная информация (профиль)**

Найдите в файле `index.html` строку:

```html
<h1>Ваше имя</h1>
```

Замените "Ваше имя" на ваше имя или никнейм.

### 2. **Описание (bio)**

Найдите строку:

```html
<p class="bio">
    Веб-разработчик, дизайнер и энтузиаст. 
    Люблю создавать красивые и функциональные цифровые решения.
</p>
```

Замените текст на ваше описание.

### 3. **Иконка профиля**

Найдите строку:

```html
<div class="profile-image">👤</div>
```

Замените `👤` на любой другой Emoji.

---

## 🔗 Редактирование ссылок социальных сетей

Найдите каждую ссылку (например Instagram):

```html
<!-- Instagram -->
<a href="https://instagram.com" class="social-link" target="_blank" rel="noopener noreferrer">
    <div class="social-link-content">
        <div class="social-icon">📷</div>
        <div>
            <div class="social-name">Instagram</div>
            <div class="social-status">@yourusername</div>
        </div>
    </div>
    <div class="social-arrow">→</div>
</a>
```

Замените:
- `https://instagram.com` → ваша полная ссылка на профиль
- `@yourusername` → ваше имя пользователя
- `📷` → нужную иконку (опционально)

### Пример заполненного профиля:

```html
<a href="https://instagram.com/alex_dev_" class="social-link" target="_blank" rel="noopener noreferrer">
    <div class="social-link-content">
        <div class="social-icon">📷</div>
        <div>
            <div class="social-name">Instagram</div>
            <div class="social-status">@alex_dev_</div>
        </div>
    </div>
    <div class="social-arrow">→</div>
</a>
```

---

## 🎨 Кастомизация стилей

### Изменение цветов

Найдите раздел `:root` в `<style>`:

```css
:root {
    --primary-color: #00d4ff;        /* Основной цвет (голубой) */
    --secondary-color: #ff006e;      /* Акцентный цвет (розовый) */
    --bg-dark: #0f0f1e;              /* Фон */
    --bg-card: #1a1a2e;              /* Цвет карточек */
    --text-light: #e0e0ff;           /* Цвет текста */
    --text-muted: #a0a0b0;           /* Приглушённый текст */
}
```

Замените hex-коды на нужные вам цвета.

### Популярные цветовые схемы:

**Пурпурная:**
```css
--primary-color: #a855f7;
--secondary-color: #ec4899;
```

**Зелёная:**
```css
--primary-color: #10b981;
--secondary-color: #34d399;
```

**Жёлтая:**
```css
--primary-color: #fbbf24;
--secondary-color: #f59e0b;
```

---

## 📱 Особенности

✅ Темная тема по умолчанию  
✅ Адаптивный дизайн (работает на мобильных и десктопе)  
✅ Плавные анимации при наведении  
✅ Анимированный фон с градиентом  
✅ SEO оптимизация  
✅ Open Graph теги для соцсетей  
✅ Встроенный favicon  
✅ Ripple эффект при клике  
✅ Быстрая загрузка (нет внешних библиотек)  

---

## 🚀 Развертывание

### Вариант 1: Локально
Просто откройте `index.html` в браузере.

### Вариант 2: На хостинге
1. Загрузите файл `index.html` на ваш хостинг
2. Готово! Сайт работает без дополнительной настройки

### Рекомендуемые хостинги:
- **Vercel** (бесплатно, быстро)
- **Netlify** (бесплатно, просто)
- **GitHub Pages** (бесплатно, через git)
- **Firebase Hosting** (бесплатно)

---

## 🔧 Meta теги (дополнительная информация)

Замените в начале файла `index.html`:

```html
<meta name="description" content="Мои социальные сети и контакты.">
```

```html
<meta property="og:title" content="Мои социальные сети">
```

```html
<meta property="og:image" content="https://via.placeholder.com/1200x630?text=Social+Links">
```

---

## 📊 Ещё можно добавить (опционально)

- Счётчик посещений
- Тёмный/светлый режим переключатель
- Дополнительные социальные сети
- QR-код
- Email контакт

---

**Все стили и скрипты встроены в один HTML файл — ничего больше не нужно!**

Удачи! 🎉
