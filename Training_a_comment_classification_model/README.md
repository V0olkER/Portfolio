# Обучение модели классификации комментариев

## Описание проекта
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

Необходимо обучить модель классифицировать комментарии на позитивные и негативные. В распоряжении набор данных с разметкой о токсичности правок.

**Условие:**
Постройте модель со значением метрики качества *F1* не меньше 0.75. 



## Навыки и инструрументы: 

* python
* pandas
* matplotlib
* seaborn
* numpy
* spacy
* nltk
* nltk.stem.WordNetLemmatizer
* ltk.corpus.wordnet
* nltk.pos_tag
* sklearn.feature_extraction.text.TfidfVectorizer 
* sklearn.metrics.f1_score
* sklearn.model_selection.train_test_split
* sklearn.linear_model.LogisticRegression
* LGBMRegressor
* CatBoostRegressor
* sklearn.model_selection.GridSearchCV
* tqdm
* sklearn.pipeline
* sklearn.make_pipeline




## Вывод
Лучшая модель удовлетворяющая требованиям заказкчика - LGBM, которая на тестовых данных показала метрику F1 0.755


