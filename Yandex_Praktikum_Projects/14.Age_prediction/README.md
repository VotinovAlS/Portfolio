# Определение возраста покупателей

[md](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/14.Age_prediction/README.md)    [ipynb](https://github.com/VotinovAlS/Portfolio/blob/master/Yandex_Praktikum_Projects/14.Age_prediction/P14_Age_prediction.ipynb)

## Описание проекта

Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.

Необходимо постройть модель, которая по фотографии определит приблизительный возраст человека.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- tensorflow.**keras**
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**
- tensorflow.keras.layers.**Dense**, **GlobalAveragePooling2D**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.optimizers.**Adam**
- tensorflow.keras.applications.resnet.**ResNet50**

## Вывод

Для решения поставленной задачи использовалась нейронная сеть ResNet50, которая позволила получить необходимые метрики за короткое время обучения.