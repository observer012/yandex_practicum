# [Прогнозирование оттока клиентов](https://github.com/observer012/yandex_practicum/blob/main/06.%20Обучение%20с%20учителем%20(10)/Прогнозирование%20оттока%20клиентов.ipynb)


## Данные

Признаки:
- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — сколько лет человек является клиентом банка
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата

Целевой признак:
- Exited — факт ухода клиента

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Задача

Подготовить модель, которая позволит спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Построить модель с предельно большим значением F1-меры, довести метрику до 0.59. 

## Используемые библиотеки
- *pandas*
- *matplotlib*
- *sklearn*
- *tqdm*

