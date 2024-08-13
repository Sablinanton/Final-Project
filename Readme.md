# Final-Project: Прогнозирование цен криптовалют

## Описание проекта

Этот проект посвящен прогнозированию цен на криптовалюты с использованием различных моделей машинного обучения. В рамках проекта были рассмотрены данные по трем криптовалютам: Bitcoin, Ethereum и Cosmos. Основная цель работы заключалась в том, чтобы выбрать наилучшую модель для прогнозирования цен криптовалют и проанализировать важность признаков.

## Данные

В проекте использовались исторические данные по ценам на закрытие, объему торгов, рыночной капитализации и другим показателям для криптовалют Bitcoin, Ethereum и Cosmos. Данные охватывают период с начала существования этих криптовалют до 2021 года.

## Задачи

1. Проведение предварительного анализа данных (EDA).
2. Масштабирование данных и создание дополнительных признаков.
3. Обучение и оценка различных моделей машинного обучения:
   - Линейная регрессия
   - Ridge-регрессия
   - Lasso-регрессия
   - Решающее дерево
   - Случайный лес
   - Градиентный бустинг
   - Метод опорных векторов (SVM)
4. Поиск аномалий в данных.
5. Оптимизация выбранной модели.
6. Анализ важности признаков для выбранной модели.

## Результаты

Лучшие результаты показала модель Линейной регрессии, которая продемонстрировала наилучшие значения метрик:
- **MSE:** 7.78e-07
- **RMSE:** 0.000882
- **MAE:** 0.000307
- **R^2:** 0.999968

## Важность признаков

Анализ важности признаков показал, что наиболее значимым признаком для прогнозирования цен является средняя цена за период (Avg Price).

## Заключение

Проект продемонстрировал возможность использования различных моделей машинного обучения для прогнозирования цен криптовалют. Линейная регрессия оказалась наилучшей моделью для данной задачи. Также были изучены важные признаки, влияющие на цену криптовалют.