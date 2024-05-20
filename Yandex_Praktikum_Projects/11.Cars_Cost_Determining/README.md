# Определение стоимости автомобилей

[HTML](https://github.com/aq2003/Portfolio/blob/main/Gold%20Recovery/P9_Portfolio.html)     [ipynb](https://github.com/aq2003/Portfolio/blob/main/Gold%20Recovery/P9_Portfolio.ipynb)

## Описание проекта

Cервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Необходимо построить модель для определения стоимости авто.

Заказчику важны: качество предсказания; скорость предсказания; время обучения.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **time**
- sklearn.model_selection.**train_test_split, GridSearchCV**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- lightgbm.**LGBMRegressor**
- catboost.**CatBoostRegressor**
- sklearn.preprocessing.**OneHotEncoder, StandardScaler**
- sklearn.compose.**make_column_transformer**
- **category_encoders**
- sklearn.metrics.**mean_squared_error**
- **warnings**
## 

## Общий вывод

Обучено 4 модели (линейная регрессия, случайный лес, CatBoostRegressor и LGBMRegressor). В результате обучения моделей наилучшей оказалась модель LGBMRegressor, она почти в 2 раза быстрее CatBoostRegressor, но при этом качество почти не отличается.