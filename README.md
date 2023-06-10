# andan_project
## Проект по прогнозированию продолжительности жизни по регионам РФ

<img src="https://cdnn21.img.ria.ru/images/07e7/05/0b/1870956348_0:45:1000:608_1920x0_80_0_0_4bcca5817339e8e1267903e22cbb4734.png" width="800">

Данный проект представляет собой анализ данных и прогнозирование продолжительности жизни в различных регионах Российской Федерации. Используя данные о различных факторах, таких как социально-экономические показатели, здравоохранение и демографические характеристики, мы стремимся определить влияние этих факторов на продолжительность жизни населения.

**Цель:** проанализировать данные, связанные с социально-экономическим положением регионов РФ и попстроить на их основе модель, которвя будет предсказывать среднюю продолжительность жизни.  

### Описание данных
Данные для анализа мы брали с сайта Росстата и приводили их к такому формату, чтобы получить out-of-time выборку
В проекте используются следующие наборы данных:
- Данные о продолжительности жизни по регионам РФ: Этот набор данных содержит информацию о средней продолжительности жизни в различных регионах России за определенные годы. Включает в себя столбцы, такие как регион, год и средняя продолжительность жизни.
- Социально-экономические показатели регионов: Этот набор данных содержит различные социально-экономические показатели регионов РФ, например, среднедушевые доходы. Он включает данные за разные годы и регионы.
- Данные о здравоохранении: Этот набор данных содержит информацию о здравоохранении в регионах России, такую как число больничных коек, мощность амбулаторно-поликлинических организаций, чиленность медецинского персонала и др.
- Экологические показателли. В данном наборе мы выбрали данные об экологическом состоянии регионов, информацию о числе предприятий, чтобы проанализировть их влияние на продолжительность жизни. 

### Cбор данных
Каждый отдельный показатель мы брали с сайта Росстата (www.gks.ru). Там они были представлены в двух форматах: таблица, которую мжно был сразу спарсить в датассет и в формате doc файлов. 
Первая часть сбора и предобрабтки данных представлена в файле [pt_1_предобрабтка](pt_1_предобрабтка.ipynb)


