# Scope — the contract in numbers

What "the game is done" means for this project. The scale is agreed in phase 1,
the numbers are refined in phase 8. Lines are never deleted — they are ticked or marked
`BLOCKED: <why>`. Counted by `scope.py`.

Line syntax:

    - [ ] <name>: <N> <unit> — count: <command that prints a number>

## Reference inventory
Sim Companies: десятки типов зданий и 100+ ресурсов, один общий рынок. Мы берём узкий срез: 1 город, 2 цепочки, 6 сфер; путь данных (`data/`) уточнится в фазе 3.

## Contract
- [ ] сферы бизнеса: 6 шт — count: ls data/businesses/*.json 2>/dev/null | wc -l
- [ ] товары (сырьё + конечные): 12 шт — count: ls data/goods/*.json 2>/dev/null | wc -l
- [ ] предметы интерьера: 20 шт — count: ls data/furniture/*.json 2>/dev/null | wc -l
- [ ] город: 1 карта — count: ls data/cities/*.json 2>/dev/null | wc -l
- [ ] события газеты: 8 шт — count: ls data/events/*.json 2>/dev/null | wc -l
