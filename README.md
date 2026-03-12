# Poker Preflop Trainer

SPA-тренажёр префлоп-решений `open-raise / fold` за `9-max` столом Texas Hold'em.

## Stack

- Vue 3 + TypeScript + Vite
- Vue Router (hash history)
- Pinia
- TailwindCSS

## Локальный запуск

```bash
npm install
npm run dev
```

Открыть локальный URL из Vite (обычно `http://localhost:5173/#/`).

## Сборка

```bash
npm run build
```

Результат будет в папке `dist/`.

## Деплой в GitHub Pages

Проект настроен под user-site репозиторий: `slava34/slava34.github.io`.

1. Убедись, что ветка деплоя — `main`.
2. В репозитории GitHub открой `Settings -> Pages`.
3. В `Build and deployment` выбери `Source: GitHub Actions`.
4. Запушь изменения в `main`.

Workflow `.github/workflows/deploy-pages.yml` автоматически:

- ставит зависимости (`npm ci`)
- собирает проект (`npm run build`)
- деплоит `dist/` в GitHub Pages

После успешного workflow сайт будет доступен на [https://slava34.github.io/](https://slava34.github.io/).




