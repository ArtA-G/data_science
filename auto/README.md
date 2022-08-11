# Определение стоимости автомобилей


## Данные

Данные о технических характеристиках, комплектации и ценах других автомобилей находятся в файле /datasets/autos.csv  

Признаки

DateCrawled — дата скачивания анкеты из базы  
VehicleType — тип автомобильного кузова  
RegistrationYear — год регистрации автомобиля  
Gearbox — тип коробки передач  
Power — мощность (л. с.)  
Model — модель автомобиля  
Kilometer — пробег (км)  
RegistrationMonth — месяц регистрации автомобиля  
FuelType — тип топлива  
Brand — марка автомобиля  
NotRepaired — была машина в ремонте или нет  
DateCreated — дата создания анкеты  
NumberOfPictures — количество фотографий автомобиля  
PostalCode — почтовый индекс владельца анкеты (пользователя)  
LastSeen — дата последней активности пользователя  
Price — цена (евро) - Целевой признак  

## Задача

Постройть модель машинного обучения, которая умеет определять цену автомабиля по его параметрам.  

Критерии, которые важны заказчику:  
качество предсказания;  
время обучения модели;  
время предсказания модели.  

## Используемые библиотеки
*pandas, numpy, matplotlib, seaborn, sklearn, catboost, lightgbm, time*