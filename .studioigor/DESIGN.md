# Design — Цепочка

A living document. Changes after playtests — with a line in "Changelog".

## Mechanics
<!-- Statuses: idea → spec → gym → playtest → locked, or cut. tier: mvp — needed
for the vertical slice; full — later. Before a mechanic — research research/mech-<id>.md. -->
| id | mechanic | tier | pillar | status | scene | notes |
|---|---|---|---|---|---|---|
| M01 | Торговая точка: меню, цены, спрос горожан-NPC, выручка (gym: кофейня с ползунками цен) | mvp | Минута решений | idea | | 30-секундный цикл; фундамент (тик экономики, склад) растёт внутри |
| M02 | Рецепты и склад: товары тратятся по рецепту, дефицит выключает позицию меню | mvp | Никто не самодостаточен | idea | | рецепты — данные, общие для всех сфер |
| M03 | Поставки: каталог предложений, договор (цена, объём, срок), доставка; NPC-оптовик ×2.5/×2 | mvp | Никто не самодостаточен | idea | | ядро идеи |
| M04 | Сфера-поставщик: производство сырья и продажа по договорам (другая сторона цепочки) | mvp | Никто не самодостаточен | idea | | та же модель рецептов |
| M05 | Репутация и надёжность: рейтинг выполнения договоров, влияет на выбор и цены | mvp | Надёжность — валюта | idea | | |
| M06 | Живой мир: аккаунты, сервер, постоянный город, бизнес работает офлайн ~8 ч | mvp | Минута решений | idea | | мультиплеер с первых тестов цепочки |
| M07 | Обустройство заведения в изометрии: предметы влияют на гостей | mvp | Моё дело видно | idea | | |
| M08 | Финансы: кредит, долги, мягкое банкротство | mvp | Минута решений | idea | | |
| M09 | Расширение: оборудование, новые товары, вторая точка, вторая сфера (макс. 2) | full | Никто не самодостаточен | idea | | |
| M10 | Городская газета: события меняют спрос и поставки | full | Минута решений | idea | | вместо сюжета |
| M11 | Час пик руками: по желанию помочь персоналу за бонус | full | Моё дело видно | idea | | необязательно |

## Game designer ideas
<!-- references/gamedesigner.md. Statuses: proposed → approved → M## | rejected (why) | deferred.
Do not propose rejected ideas again. Do not implement unapproved ones. -->
| id | idea | why it's fun | cost S/M/L | point (phase) | status |
|---|---|---|---|---|---|

## Content
<!-- phase 8 (references/production.md): one line per unit. Statuses: sketch → blockout → art → final. -->
| id | new | signature moment | difficulty 1–10 | axes of difference from the neighbor | story beat | status |
|---|---|---|---|---|---|---|

## Progression and meta
- старт: 1 сфера, стартовый капитал; рост: оборудование → новые товары → 2-я точка → 2-я сфера (максимум 2 — цепочку целиком не закрыть)
- мягкое банкротство: бизнес теряется, опыт и часть репутации остаются

## Economy
<!-- resource: sources → sinks, rate (a guess is fine) -->
- деньги: продажи горожанам-NPC и другим игрокам → закупки, аренда, зарплаты, оборудование, проценты по кредиту, наценка NPC-оптовика
- товары MVP: сырьё/полуфабрикаты — обжаренные зёрна, молоко, сахар, мука; конечные — напитки кофейни и выпечка пекарни
- NPC-оптовик: цена ×2.5, срок ×2 — потолок цены для игроков-поставщиков
- склад ограничивает офлайн-работу (~8 ч)

## Difficulty
- philosophy: мягкий вход (стартовый капитал, NPC-оптовик), сложность растёт от конкуренции и зависимостей, а не от цифр
- axes: число зависимостей бизнеса, конкуренция в сфере, события газеты

## Mechanic specs
<!-- ### M01 — Name
what · why (pillar) · controls · rules · parameters (in data files) ·
acceptance criteria · "feel" (targets) · research: research/mech-M01.md -->

## Changelog
| date | what | why |
|---|---|---|
