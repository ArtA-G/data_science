# Прогнозирование оттока клиентов оператора связи

## Данные

Данные состоят из 4-х файлов:  
• contract.csv — информация о договоре;  
• personal.csv — персональные данные клиента;  
• internet.csv — информация об интернет-услугах;  
• phone.csv — информация об услугах телефонии.  
Во всех файлах столбец customerID содержит код клиента.

Описание полей данных:  
BeginDate – дата начала пользования услугами,  
EndDate – дата окончания пользования услугами,  
Type – тип оплаты: ежемесячный, годовой и тд,  
PaperlessBilling – безналичный расчет,  
PaymentMethod – способ оплаты,  
MonthlyCharges – ежемесячные траты на услуги,  
TotalCharges – всего потрачено денег на услуги  
Dependents – наличие иждивенцев  
Senior Citizen – наличие пенсионного статуса по возрасту  
Partner – наличие супруга(и)  
MultipleLines – наличие возможности ведения параллельных линий во время звонка


## Задача

Создание модели машинного обучения для прогнозирования оттока клиентов оператора связи.  
Прогноз по каждому клиенту будет формировать модель машинного обучения в виде бинарной классификации "1" - клиент уйдет, "0" - клиент не уйдет. Качество прогнозирования будет определятся метриками ROC AUC И Accuracy/

## Используемые библиотеки
*pandas, numpy, datetime, matplotlib, seaborn, sklearn, catboost*
