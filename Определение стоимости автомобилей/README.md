# Описание проекта

Необходимо построить модель, которая умеет её определять. В распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей.

Критерии, которые важны заказчику:

- качество предсказания;
- время обучения модели;
- время предсказания модели.

## Используемый стек

- Python
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- Catboost
- LightGBM
- Numpy

# Вывод

Лучшей моделью по качеству можно признать `LGBMRegressor`. Время обучения около 6 минут. `RMSE` \= `1575.6321` тренировочной выборке и `1570.6206` на тестовой выборке.

# Статус

Проект завершён.