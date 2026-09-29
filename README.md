# Цифровой помощник тьютора — тестовое задание BA + Project Manager

Тестовое задание для отбора на проект **«Академия маленьких наук»**, направление **AI-агент для анализа наблюдений за детьми с ОВЗ**.

## Контекст задачи

Тьюторы, специалисты, родители и врачи ведут наблюдения за ребёнком в разрозненном виде (Excel, заметки, устные отчёты). Из-за этого сложно увидеть динамику, найти закономерности (например, «недосып → агрессия») и вовремя скорректировать индивидуальный образовательный маршрут (ИОМ).

Нужно спроектировать AI-агента и цифровое пространство, которое:
- собирает наблюдения по единому шаблону;
- визуализирует динамику для каждой роли (тьютор, родитель, специалист, врач);
- формирует AI-подсказки с указанием данных, на которых они основаны;
- разграничивает доступ к данным ребёнка по ролям.

Стек по ТЗ заказчика: **React + TypeScript** (frontend), **Python** (backend), **PostgreSQL**, **S3** (файлы/видео), **GigaChat** (LLM). Есть данные пилотной апробации на 9 детях (РАС, ЗПР, тяжёлые нарушения речи).

## Что внутри репозитория

| Раздел | Что это | Файл |
|---|---|---|
| Вопросы стейкхолдерам | 8 вопросов с указанием, кому, зачем и какой риск закрываем | [`src/01-stakeholder-questions.xlsx`](./src/01-stakeholder-questions.xlsx) |
| Бизнес-процесс | Процесс «Внесение и структурирование наблюдений тьютором» + BPMN-подобная схема | [`src/02-process-observation-entry.pdf`](./src/02-process-observation-entry.pdf) |
| Дорожная карта пилота | 8 недель, вехи, критерии готовности, роли, риски | [`src/03-pilot-roadmap.xlsx`](./src/03-pilot-roadmap.xlsx) |
| Работа с заказчиком и командой | Формат, частота, фокус коммуникации | [`src/04-team-communication.pdf`](./src/04-team-communication.pdf) |

### Проектное решение (как если бы аналитика была завершена)

| Артефакт | Файл |
|---|---|
| Функциональные требования | [`solution/01-functional-requirements.md`](./solution/01-functional-requirements.md) |
| Нефункциональные требования | [`solution/02-non-functional-requirements.md`](./solution/02-non-functional-requirements.md) |
| Матрица ролей и доступа | [`solution/03-roles-access-matrix.md`](./solution/03-roles-access-matrix.md) |
| User Stories (беклог) | [`solution/04-user-stories.md`](./solution/04-user-stories.md) |
| Модель данных (ER) | [`solution/05-data-model.md`](./solution/05-data-model.md) |
| API-контракт | [`solution/06-api-contract.md`](./solution/06-api-contract.md) |
| Логика AI-модуля | [`solution/07-ai-module-logic.md`](./solution/07-ai-module-logic.md) |
| Метрики успеха | [`solution/08-success-metrics.md`](./solution/08-success-metrics.md) |

Диаграммы — в [`diagrams/`](./diagrams).
