# Определение стоимости автомобилей

## Описание проекта

Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Вам нужно построить модель для определения стоимости. 

Заказчику важны:

- качество предсказания;
- скорость предсказания;
- время обучения.



## Навыки и инструрументы: 

* python
* pandas
* matplotlib
* numpy
* sklearn.preprocessing.OneHotEncoder
* sklearn.preprocessing.StandardScaler
* sklearn.preprocessing.OrdinalEncoder 
* sklearn.model_selection.train_test_split
* sklearn.ensemble.RandomForestRegressor
* sklearn.linear_model.LinearRegression
* sklearn.metrics.mean_squared_error
* LGBMRegressor
* CatBoostRegressor


## Вывод
При проверки моделей на валидационной выборке было принято решение взять модель CatBoos, так как она показала лучшие результаты и оптимальное время работоспособности. 

Проверка на тестовых данных показало положительные результаты метрики RMSE 1563.79
