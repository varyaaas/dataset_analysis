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
