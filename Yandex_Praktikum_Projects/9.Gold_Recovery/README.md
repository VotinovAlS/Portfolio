# Улучшение процесса обогащения золота

[md](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/9.Gold_Recovery/README.md)     [ipynb](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/9.Gold_Recovery/P9_Gold_Recovery.ipynb)

## Описание проекта

Требуется подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_absolute_error**, **make_scorer**
- sklearn.preprocessing.**StandardScaler**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**


## 

## Общий вывод

Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.