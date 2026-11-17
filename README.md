# TempoTask

Недельный таск-менеджер с вкладкой «Флекс» (задачи без даты). Работает как сайт и как Telegram Mini App.

- Один файл `index.html`, сборка не нужна.
- React, Tailwind и htm подключены с CDN (`cdn.jsdelivr.net`, `cdn.tailwindcss.com`).
- Данные хранятся в `localStorage` браузера, отдельно для каждого домена и устройства.
- Языки: русский, украинский, английский. Есть тёмная тема, экспорт и импорт JSON в настройках.

## Выкладка на GitHub Pages

Через терминал (замени `USER` и `REPO` на свои):

```bash
cd /путь/к/tempotask
git init
git add .
git commit -m "TempoTask"
git branch -M main
git remote add origin https://github.com/USER/REPO.git
git push -u origin main
```

Потом на GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main, папка / (root) → Save**.

Через минуту сайт будет по адресу `https://USER.github.io/REPO/`.

## Подключение к Telegram

1. Открой @BotFather.
2. Для кнопки меню: `/mybots` → твой бот → **Bot Settings → Menu Button → Configure menu button**, вставь ссылку на Pages.
3. Или создай Mini App: `/newapp`, в поле URL та же ссылка.

После этого в Telegram подтянутся имя и фото профиля, а язык интерфейса выберется по языку Telegram.

## Управление

- Компьютер: перетаскивай карточки из Флекса на нужный день и час.
- Телефон: удерживай карточку или блок около 0,3 секунды, потом тяни.
