# Восстановление золота из руды

## Описание проекта
Подготовить прототип модели машинного обучения. Компания разрабатывает решения для эффективной работы промышленных предприятий.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Предоставленны данные с параметрами добычи и очистки.

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.



## Навыки и инструрументы: 

* python
* pandas
* matplotlib
* seaborn
* numpy
* sklearn.metrics.make_scorer
* sklearn.model_selection.train_test_split
* sklearn.preprocessing.StandardScaler
* sklearn.model_selection.cross_val_score
* sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor
* sklearn.model_selection.GridSearchCV
* sklearn.dummy.DummyRegressor




## Вывод
На основе исследований с задачей справилась модель случайного леса, показав метрику sMAPE 7.36, в то время как показатели констаной модели равны 9.16. Благодаря использованию подготовленной модели мы можем получить лучшую оценку результата процесса обогащения.
