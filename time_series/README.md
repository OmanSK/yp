# TimeSeries-Jupyter
![Analysis](https://img.shields.io/badge/Analysis-827141?style=flat)
![TimeSeries](https://img.shields.io/badge/TimeSeries-827141?style=flat)
![Statsmodels](https://img.shields.io/badge/Statsmodels-827141?style=flat)
![Catboost](https://img.shields.io/badge/Catboost-cf8378?style=flat)
![Pytorch](https://img.shields.io/badge/Pytorch-cf8378?style=flat)
![NeuralProphet](https://img.shields.io/badge/NeuralProphet-cf8378?style=flat)

<br />
<div align="center">
  <a>
    <img src="https://www.dataquest.io/wp-content/uploads/2018/11/time-series-pandas_78_0.png" alt="Logo" width="320" height="160">
  </a>

  <h3 align="center">TimeSeriesPrediction</h3>
</div>

## About The Project

Предсказание потребности в автомобилях такси на следующий час на основании исторических данных о загруженности такси.
Цель подобной работы:
* Сокращение издержек на выплаты по причине простоя водителей 
* Ориентация на час вперед позволит заранее предсказать минимальное число машин, которые должны быть на смене

Что сделано:
* Анализ временного ряда, работа по подготовке данных (устранение тренда)
* Создание моделей классического ML (бустинг и анализ sarima) для предсказания на 1 час вперед
* Создание моделей глубокого обучения (реккурентная сеть LSTM, NeuralProphet) для предсказания на 2 часа и на час вперед соответственно
* Вывод и выбор лучшей модели

