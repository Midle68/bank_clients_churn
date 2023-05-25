# Проект "Отток клиентов"

## Описание проекта:

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Необходимо построить модель с предельно большим значением **F1**-меры: > 0.59.

Дополнительно измеряется **AUC-ROC** и сравнивается с значением **F1**-меры.

*Источник данных*: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## План проекта: 

 1. [Подготовка данных](#data_preparation)
 2. [Исследование задачи](#task_research) (рассмотрение моделей без учета дисбаланса классов)
 3. [Борьба с дисбалансом](#fighting_imbalance) (применение методов с целью устранения дисбаланса класса и рассмотрение показателя f1_score)
 4. [Тестирование моделей](#model_testing) (на тестовой уже выборке)

## Решенные задачи:
1) Подготовлены данные;
2) Исследованы задачи без учета дисбаланса классов;
3) Применены методы для утсранения дисбаланса и рассмотрение значений F1-меры;
4) Тестирование моделей. Получено значение показателя **F1** – 0.63, **ROC-AUC** – 0.77.

## Используемые библиотеки:

`matplotlib`, `numpy`, `pandas`, `sklearn`
