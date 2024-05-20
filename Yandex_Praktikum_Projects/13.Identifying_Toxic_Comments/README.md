# Обучение модели классификации комментариев

[md](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/13.Identifying_Toxic_Comments/README.md)    [ipynb](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/13.Identifying_Toxic_Comments/P13_Identifying_Toxic_Comments.ipynb)

## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **spacy**
- **matplotlib**
- **stopwords**
- sklearn.model_selection.**train_test_split**, **GridSearchCV**, **cross_val_score**
- sklearn.metrics.**f1_score**, **roc_auc_score**, **roc_curve**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**



## Вывод

Была проведена исследовательская работа по обработке текстов, обучению и выбору модели для определения токсичных комментариев по методу TF-IDF. Выбрана логистическая регрессия, которая показала наилучшее качество.