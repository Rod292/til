# shell : xargs -P pour paralléliser

`... | xargs -P 4 -I{} cmd {}` lance quatre traitements en parallèle.
