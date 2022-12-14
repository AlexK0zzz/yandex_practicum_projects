# churn_presiction

## Прогнозирование оттока клиентов телеком-компании

Оператор связи для минимизации убытков хочет прогнозировать отток клиентов. Если обнаружится, что клиент собирается уходить, то ему будут предложены промокоды или специальные условия, чтобы удержать его.

**Цель работы** -- построение модели, которая будет предсказывать уход клиента.

**Входные данные** -- информация о клиентах, данные об их договорах и используемых услугах (на 01.02.2020).

**План проекта**
 1. **Предобработка данных** (проверка данных на пропуски/дубликаты/аномалии и исправление обнаруженных ошибок)
 0. **Подготовка данных** (объединение таблиц, генерация новых признаков и/или удаление лишних)
 0. **Исследовательский анализ данных** (построение распределений признаков, определение закономерностей)
 0. **Обучение и сравнение моделей** (выбор нескольких моделей, определение оптимальных гиперпараметров и обучение на кросс-валидации, выбор лучшей модели)
 0. **Тестирование лучшей модели**
 
**Результаты**

На основании полученных резльтатов в качестве итоговой модели был выбран `CatBoostClassifier` с параметрами `learning_rate=0.2, iteration=450, depth=6`. На тестовой выборке эта модель показала результат `ROC-AUC=0.92` и `accuracy=0.88`.