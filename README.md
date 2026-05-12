# fitflow-bare

Минимальный контекст для FitFlow — вымышленного мобильного фитнес-приложения. Это репо используется как **A/B-контраст** к [Working-in-IT/fitflow-rich](https://github.com/Working-in-IT/fitflow-rich) в вебинаре [Podlodka ProductCrew](https://podlodka.io/productcrew) «Агентная аналитика для продактов».

## Что внутри

- `data/fitflow.db` — SQLite-база с двумя таблицами (`events`, `feedback`). 107К событий + 1.1К отзывов.
- Никакого `CLAUDE.md`, документации схемы, skills или продуктового контекста — это намеренно.

## Зачем

Это репо демонстрирует, что происходит, когда AI-агент работает с данными **без контекста продукта**. Тот же агент, тот же вопрос, но без `PRODUCT_CONTEXT.md`, `data/README.md` и skill-pack — даёт generic-вывод вместо product-grounded analysis.

Сравнение — в [fitflow-rich](https://github.com/Working-in-IT/fitflow-rich).

## Лицензия

MIT — см. [LICENSE](LICENSE).

## Кредиты

- Оригинальные данные: [Working-in-IT/agentic-analytics-workshop](https://github.com/Working-in-IT/agentic-analytics-workshop)
- Вдохновение для skill-pack (см. fitflow-rich): [nimrodfisher/data-analytics-skills](https://github.com/nimrodfisher/data-analytics-skills)
