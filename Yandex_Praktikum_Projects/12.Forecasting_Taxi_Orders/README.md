# Прогноз количества заказов для сервиса такси

[md](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/12.Forecasting_Taxi_Orders/README.md)     [ipynb](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/12.Forecasting_Taxi_Orders/P12_Forecasting_Taxi_Orders.ipynb)

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