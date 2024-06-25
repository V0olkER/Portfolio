# Прогнозирование заказов такси

## Описание проекта

Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.

**Условие:**

Значение метрики *RMSE* на тестовой выборке должно быть не больше 48.





## Навыки и инструрументы: 

* python
* pandas
* matplotlib
* numpy
* statsmodels.tsa.seasonal.seasonal_decompose
* sklearn.model_selection.train_test_split
* sklearn.ensemble.RandomForestRegressor
* sklearn.linear_model.LinearRegression
* sklearn.metrics.mean_squared_error
* LGBMRegressor
* CatBoostRegressor


## Вывод
Модель CatBoost справилась с поставленной задачей и показала на тестовых данных метрику RMSE = 44,9

