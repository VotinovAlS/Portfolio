# Предсказание температуры сплава

[md](https://github.com/aq2003/Portfolio/blob/main/Analyzing%20Texts/P13_Portfolio.md)    [ipynb](https://github.com/aq2003/Portfolio/blob/main/Analyzing%20Texts/P13_Portfolio.ipynb)

## Описание проекта

Чтобы оптимизировать производственные расходы, металлургический комбинат «Стальная птица» решил уменьшить потребление электроэнергии на этапе обработки стали. Задача — построить модель, которая будет предсказывать температуру этого сплава.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- **matplotlib**
- **re**
- **shap**
- sklearn.model_selection.**train_test_split**, **GridSearchCV**, **cross_val_score**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- lightgbm.**LGBMRegressor**
- catboost.**CatBoostRegressor**

## Вывод

Обучено 4 модели(линейная регрессия, случайный лес, CatBoostRegressor и LGBMRegressor), наилучшей оказалась модель случайного леса.