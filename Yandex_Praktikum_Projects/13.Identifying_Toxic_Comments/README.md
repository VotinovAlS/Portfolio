# Обучение модели классификации комментариев

[md](https://github.com/aq2003/Portfolio/blob/main/Analyzing%20Texts/P13_Portfolio.md)    [ipynb](https://github.com/aq2003/Portfolio/blob/main/Analyzing%20Texts/P13_Portfolio.ipynb)

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