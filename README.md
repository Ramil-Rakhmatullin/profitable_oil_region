## profitable_oil_region
# Проект, задача которого выбрать наиболее прибыльный для разработки нефтяной регион

Задача данного проекта - выбрать один из трех районов, который будет самым прибыльным для дальнейшей разработки. Были предоставлены пробы нефти в трёх регионах.
Характеристики для каждой скважины в регионе уже были известны.

**Ход реализации проекта:**

- датасеты были изучены, предобработка не потребовалась;
- каждый из регионов был проанализирован отдельно, для каждого из них были построены гистограммы объема запасов в скважине;
- для каждого из регионов была обучена модель, сделаны предсказания на валидационных выборках, рассчитаны RMSE модели;
- посчитаны минимально необходимые запасы скважины для ее безубыточной разработки;
- применена техника Bootstrap с 1000 выборок, чтобы найти распределение прибыли. Выбирались 500 скважин и оставлялись для дальнейшей работы 200 лучших;
- найдена средняя прибыль, 95% доверительный интервал и риск убытков для каждого из регионов;
- найден самый прибыльный регион и сделаны выводы.
