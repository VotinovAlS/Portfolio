# Прогноз количества заказов для сервиса такси

[HTML](https://github.com/aq2003/Portfolio/blob/main/Taxi%20Service/P12_Portfolio.html)     [ipynb](https://github.com/aq2003/Portfolio/blob/main/Taxi%20Service/P12_Portfolio.ipynb)

## Описание проекта

Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- statsmodels.tsa.seasonal.**seasonal_decompose**, **adfuller**
- sklearn.model_selection.**train_test_split**, **TimeSeriesSplit**, **GridSearchCV**, **cross_val_score**
- sklearn.metrics.**mean_squared_error**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- lightgbm.**LGBMRegressor**
- catboost.**CatBoostRegressor**
- sklearn.dummy.**DummyRegressor**
- sklearn.preprocessing.**StandardScaler**

## 

## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование трёх типов моделей, наилучшей оказалась модель LGBMRegressor.