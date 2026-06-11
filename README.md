# healthmaster-site

Сайт healthmaster.app живёт здесь.

Хостится на Netlify (Site ID `bd9a2b75-3ec0-4a3a-9051-d58c17ccbfa8`).

## Деплой

```
npx netlify-cli deploy --prod --dir=.
```

Нужен `netlify login`.

## Структура

- `eng/` — английские страницы
- `rus/` — русские страницы
- корень — root-страницы (`link.html`, `privacy-ru.html`, `terms-ru.html`, `_redirects`)
