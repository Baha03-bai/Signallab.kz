# SignalLab Landing

Готовый лендинг для GitHub Pages.

## Что изменено в этой версии
- убрана картинка с главного экрана
- hero заменён на чёткий SVG/UI-визуал без потери качества
- улучшены пропорции экранов
- доработаны размеры шрифтов, карточек и отступов
- адаптив mobile first
- RU / KZ переключатель
- форма заявки + WhatsApp
- заготовки под GA4 и Meta Pixel

## Структура
- `index.html`
- `styles.css`
- `script.js`

## Что заменить перед публикацией
1. В `index.html` замените:
   - `G-XXXXXXXXXX` на ваш GA4 ID
   - `YOUR_PIXEL_ID` на ваш Meta Pixel ID
   - `https://formspree.io/f/YOUR_FORM_ID` на ваш Formspree endpoint
   - `https://example.com` на ваш домен

## Публикация на GitHub Pages
```bash
git init
git add .
git commit -m "SignalLab landing v3"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

Потом в GitHub:
- `Settings`
- `Pages`
- Source → `Deploy from a branch`
- Branch → `main` / `/root`

## Подключение домена
1. В настройках Pages укажите домен.
2. У регистратора домена добавьте DNS записи:
   - `A` записи на IP GitHub Pages
   - `CNAME` для `www` на ваш GitHub Pages адрес
3. Включите `Enforce HTTPS`.
