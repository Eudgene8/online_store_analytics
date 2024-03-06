**Аналитика интернет магазина**

**Цель исследования:** Вместе с отделом маркетинга подготовлен список гипотез для увеличения выручки. Необходимо приоритизировать гипотезы, запустите A/B-тест и проанализировать результаты.

**Ход исследования:**
Данные берем из трех файлов:
hypothesis.csv
orders.csv
visitors.csv
В которых содержится информация о гипотезах, заказах и пользователях. На основании полученных файлов проведем исследование.

**Навыки и инструменты:**
- pandas
- datetime
- numpy
- matplotlib.pyplot
- scipy.stats
- A/B-тестирование
- проверка статистических гипотез

**Общий вывод:**

- В среднем количестве заказов между группами есть статистически значимые отличия как по "сырым" данным, так и после фильтрации аномалий.
- Статистически значимых отличий в среднем чеке нет.
- График различия средниго количества заказов на посетителя между группами сообщает, что результаты группы B лучше группы A. Прирост группы В закрепился в районе 15%.
- График среднего чека показывает что результаты группы В лучше.
- При этом каких-то явных аномалий влияющих на реузльтат мы не выявили.

В результате проделанной работы приходим к выводу, что нужно остановить тест и зафиксировать победу группы В.