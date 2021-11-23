# KC_redash

https://redash.lab.karpov.courses/dashboards/249-tsukanov_sales_dashboard

Взял за тему отдел продаж.

Все основные графики, отражающие общую картину датасета (без углубления в специфику стран, поскольку очевидно, что подавляющее число заказов приходится на Великобританию).

Составил следующие показатели:

<li> Total Revenue, 2011Y - общая выручка за 2011 год, поскольку датасет содержит также информацию за другой неполный год;
<li> TOP-5 Revenue countries - топ-5 стран по выручке. Здесь по году делить не стал, взял в целом. Так как сказано, что интернет-магазин британский, то получается, что почти все продажи приходятся на домашний рынок.
TOP-5 Products - топ-5 товаров по заказам. Само название запроса говорит за себя)
<li> Total Revenue per Month - общая выручка в разбивке по месяцам. Так мы можем отследить возможный тренд (закономерность) получения выручки от месяца. Очевиден факт, что Осень-зима показывает бОльший прирост выручки, чем остальные сезоны и месяцы по отношению к друг другу. Декабрь в расчет не берем - данные за месяц были не полными.
<li> Payday trendline - тоже самое, что и предыдущий, только с более углубленной разбивкой - по дням. Можно было, конечно, сделать с применением окна, чтобы немного сгладить график.
<li> Orders/Customers per Week - попытка отловить корреляцию между числом заказов и кол-ом покупателей, разбивка по неделям. Можно отметить, что связь есть.
<li> Revenue shares geo - Доли выручки по странам в графическом виде. Чисто для красоты! :) 
