# Выбор локации для скважины

## Данные

Данные геологоразведки трёх регионов находятся в файлах:
/datasets/geo_data_0.csv.  
/datasets/geo_data_1.csv.  
/datasets/geo_data_2.csv.  


## Задача

Построить модель для определения региона, где добыча принесёт наибольшую прибыль.  
Проанализировать возможную прибыль и риски. 


Условия задачи:  
Для обучения модели подходит только линейная регрессия (остальные — недостаточно предсказуемые).  
При разведке региона исследуют 500 точек, из которых с помощью машинного обучения выбирают 200 лучших для разработки.  
Бюджет на разработку скважин в регионе — 10 млрд рублей.  
При нынешних ценах один баррель сырья приносит 450 рублей дохода. Доход с каждой единицы продукта составляет 450 тыс. рублей, поскольку объём указан в тысячах баррелей.  
После оценки рисков нужно оставить лишь те регионы, в которых вероятность убытков меньше 2.5%. Среди них выбирают регион с наибольшей средней прибылью.  

## Используемые библиотеки
*pandas, numpy, sklearn, scipy, matplotlib, seaborn, math*
