# Static site starter for Dada Cloud

[![Deploy to Dada Cloud](https://img.shields.io/badge/Deploy%20to-Dada%20Cloud-2563eb?style=for-the-badge)](https://cloud.dada-tuda.ru/deploy?repo=DadaDevelopment/dada-static-starter&utm_source=github_template&utm_campaign=static)

Минимальный статичный сайт, готовый к деплою из GitHub в **[Dada Cloud](https://cloud.dada-tuda.ru)** — российское облако для разработчиков.

## Зачем это нужно

Простой лендинг или портфолио проще держать в России: деплой из GitHub, оплата рублями, данные в РФ (152-ФЗ), HTTPS из коробки. Есть бесплатный тариф.

## Как задеплоить

1. Нажми **Use this template → Create a new repository** (или форкни репозиторий).
2. Зарегистрируйся на [cloud.dada-tuda.ru](https://cloud.dada-tuda.ru/deploy?repo=DadaDevelopment/dada-static-starter&utm_source=github_template&utm_campaign=static).
3. Подключи свой GitHub, выбери этот репозиторий — Dada соберёт образ по `Dockerfile` (nginx) и выдаст HTTPS-домен.
4. Каждый `git push` пересобирает сайт автоматически.

## Локальный запуск

Просто открой `index.html` в браузере, или:

```bash
docker build -t site . && docker run -p 8080:80 site
# http://localhost:8080
```

## Лицензия

MIT — используй как хочешь.
