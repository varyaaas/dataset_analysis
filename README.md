# Анализ датасетов на Python

## Fastfood analysis
Ноутбук [fastfood_analysis.ipynb](./fastfood_analysis.ipynb) содержит анализ датасета [Fastfood Nutrition](https://www.kaggle.com/datasets/ulrikthygepedersen/fastfood-nutrition) с kaggle.

Датасет содержит информацию о различных блюдах из популярных сетей быстрого питания в США. 
В нем собрана информация о ресторанах (Mcdonalds, Taco Bell, Subway, ...), блюдах (Artisan Grilled Chicken Sandwich, Single Bacon Smokehouse Burger) и их пищевой ценности. 

**Выводы:**

1) Чем калорийнее блюдо, тем выше в нем содержание жиров ($\alpha = 0.05$).

2) Количество кальция в блюдах не имеет нормальное распределение ($\alpha = 0.05$).

3) Построена линейная регрессия для определения количества жира по калорийности.

4) Еда датасета была кластеризована на три кластера: "полезная", "средне вредная", "вредная".

5) Ресторан Taco Bell вляется лидером по "полезной" еде. Еда в Burger King, Макдональдс и Sonic в основном вредная или средне вредная. 

## Pokemon analysis
Ноутбук [pokemon_analysis.ipynb](./pokemon_analysis.ipynb) содержит анализ датасета [Pokemon with stats](https://www.kaggle.com/datasets/abcsds/pokemon) c kaggle.

В изучаемом датасете «Pokemon with stats» находится информация обо всех известных на 2016 год покемонах. Этот набор данных включает в себя 800 строк (721 уникальных покемонов), а также их основные характеристики: 

Идентификатор покемона, имя покемона, класс покемона, дополнительный класс покемона, сумма по всем числовым характеристикам покемона, очки здоровья покемона, сила атаки покемона, очки защиты покемона, сила специальной атаки покемона, сила защиты от специальных атак, скорость покемона, номер поколения покемона, принадлежность покемона к легендарным. 

**Выводы**

1. Можно утверждать о различии характеристик легендарных и обычных покемонов $(\alpha = 0.05)$.

2. Доверительный интервал для доли легендарных покемонов -$[0,0197; 0,1203]\ \   (\alpha = 0.05)$

3. В достаточно грубом приближении драконий тип покемонов является одним из лучших типов в игре - по проценту легендарных карт и по силе атаки.

4. Уравнение линии тренда зависимости очков здоровья от очков атаки имеет вид:
$$y = 0.333x + 43\ (R^2 = 0.1784,\   p-value = 5.89e-36)$$


