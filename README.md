# fitflow-bare

Минимальный контекст для FitFlow — вымышленного мобильного фитнес-приложения. Это репо используется как **A/B-контраст** к [Working-in-IT/fitflow-rich](https://github.com/Working-in-IT/fitflow-rich) в вебинаре [Podlodka ProductCrew](https://podlodka.io/productcrew) «Агентная аналитика для продактов».

## 🚀 Идёшь на воркшоп?

Чтобы работать руками во время эфира — пройди [**SETUP.md**](SETUP.md) **за день до воркшопа**. Там пошаговая инструкция: Python, git, VS Code, Claude Code, доступ к Claude и smoke test. Время на подготовку — 30–45 минут с нуля.

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
