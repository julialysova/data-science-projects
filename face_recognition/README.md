# Определение возраста покупателей

Посмотреть проект в Jupyter nbviewer: https://nbviewer.jupyter.org/github/julialysova/data-science-projects/blob/main/face_recognition/age_recognition.ipynb

## Данные

В нашем распоряжении были фотографии лиц людей различных возрастов (от 1 года до 99 лет)

## Задача

Построить нейросеть, способную определить возраст покупателя для дальнейшего предложения им интересных товаров, либо для контроля возраста при покупке алкоголя. Использовалась сеть ResNet, обученная на данных ImageNet

## Результаты

С помощью видоизмененной нейросети ResNet50 получилось достичь метрики MAE в 7,5 лет.

## Используемые библиотеки
*pandas*, *seaborn*, *numpy*, *matplotlib*, *tensorflow*