# 🌙 Rem's Elegant Night Theme для Shikimori
Тёмно-синяя тема в стиле Рем из Re:Zero с анимированными элементами и адаптивным дизайном

![Скриншот](https://i.ibb.co/nvz5jhP/9cb5bd37bc9818e1a5eca60c4578a83c.png) - Фон на пк по умолчанию (можно заменить),

![Скриншот](https://i.ibb.co/4gwT70P1/ec8c6de737e19e47db794ce577686947.jpg) - Фон на телефоне по умолчанию (тоже можно заменить)
## 🛠 Установка
1.Установи расширение Stylus для Chrome / Firefox

2.Нажми → RAW-ссылка на CSS

3.В Stylus выбери «Установить стиль»

Или вручную:

```css
@import url("@import url("https://raw.githubusercontent.com/Dream-Mercy/Rem-theme/main/Rem-theme-shiki/theme.css");");
```
## 🎀 Особенности темы
Цветовая палитра Рем: глубокие синие и розовые оттенки

Анимированный аватар с эффектом ледяного сияния

Кастомные курсоры в форме рога Рем

Адаптивный дизайн для ПК и мобильных устройств

Динамические рейтинги с цветовой индикацией

### 🎨 Цветовая схема
```css
:root {
  --rem-blue: #7ec0ee;       /* Цвет глаз */
  --rem-pink: #e83b6a;       /* Цвет роз/крови */
  --rem-dark: #1a1a2e;       /* Тёмный фон */
  --rem-light: #f0f0ff;      /* Светлый текст */
}
```
## 🌟 Ключевые элементы
### ❄️ Анимированный аватар
```css
.profile-head .avatar {
  animation: iceGlow 4s linear infinite;
}
@keyframes iceGlow {
  0% { transform: rotate(30deg) translate(-30%, -30%); }
  100% { transform: rotate(30deg) translate(30%, 30%); }
}
```
### 🦄 Кастомный курсор
```css
body {
  cursor: url('https://i.ibb.co/0nQ7zJX/rem-horn-cursor.png'), auto !important;
}
```
### 📊 Рейтинги
Оценка	Цвет	Пример
9-10	Розовый	![9]
7-8	Голубой	![7]
5-6	Золотой	![5]
## 📱 Адаптивность
ПК-версия: параллакс-фон, сложные анимации

Мобильная версия: упрощённый дизайн (main_code_4mob.css)

```css
@media (max-width: 768px) {
  body { background: url('https://i.ibb.co/4gwT70P1/ec8c6de737e19e47db794ce577686947.jpg') !important; }
}
```
## 🐞 Отчёт о багах
Нашли ошибку? Создайте issue с:

1.Скриншотом

2.Версией браузера

3.Шагами для воспроизведения
## 💡 Советы по кастомизации
1.Сменить фон:

```css
body::after {
  background-image: url("ВАША_ССЫЛКА.jpg");
}
```
2.Изменить акцентный цвет:

```css
:root {
  --rem-pink: #ВАШ_ЦВЕТ;
}
```
## 🚀 Идеи для развития
1.**Добавить переключатель «День/Ночь»**

2.**Анимация падающих розовых лепестков**

3.**Саунд-эффекты при наведении**
## Автор: Dream_Mercy
Вдохновение: Рем (Re:Zero), сине-розовые палитры

«Я — Рем, ваша верная горничная» © Re:Zero

## 📸 Скриншоты
![Скриншот](https://i.ibb.co/jPNNTbj0/image.png)
![Скриншот](https://i.ibb.co/nsZQ2S3v/image.png)
![Скриншот](https://i.ibb.co/VcgHwp5R/image.png)

При наведении курсора:
![Скриншот](https://i.ibb.co/Z1VHysPV/image.png)
![Скриншот](https://i.ibb.co/jPFcYKxC/image.png)
