# Определение стоимости автомобилей
Посмотреть проект в Jupyter nbviewer: https://nbviewer.jupyter.org/github/julialysova/study-projects/blob/main/car_price_regression/regression_for_car_prices.ipynb

## Описание данных

Для анализа были представлены данные о различных автомобилях, выставленнх на продажу, влючая тип кузова, год регистрации , тип коробки передач, мощность, модель, пробег, дату регистрации, марку, наличие ремонта и т.п.

## Задача

Построить модель для определения стоимости автомобилей, чтобы использовать ее в приложения для расчета рыночной стоимости автомобилей на продажу. Необходимо выделить признаки, имеющие влияние на стоимость авто, провести обработку данных и выбрать наилучшую регрессионную модель.

## Результаты

Наименьшая ошибка (RMSE) в предсказаниях была получена с помощью LightGBM, однако модель оказалась самой медленной, а заказчику важна скорость. Поэтому выбор пал на DecisionTree, давший самый быстрый ответ с относительно небольшой ошибкой.

## Используемые библиотеки

*pandas*, *requests*, *numpy*, *scipy*, *sklearn*, *datetime*, *lightgbm*

