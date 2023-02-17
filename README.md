# Yandex.Praktikum Data Science Projects

Репозиторий с проектами, реализованными в рамках профессии "Специалист по Data Science" в Яндекс.Практикуме

## Описание проектов:

| Название проекта | Задачи проекта| Используемые технологии|
|-|-|-|
|1. [Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов](https://github.com/kama8ullet/Yandex/blob/main/01_Yandex_music/Yandex_music.ipynb)|На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.| `Python` `Pandas`|
|2. [Исследование надёжности заёмщиков — анализ банковских данных](https://github.com/kama8ullet/Yandex/blob/main/02_Data_processing/Data_processing.ipynb)|На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок.|`Python` `Pandas`|
|3. [Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](https://github.com/kama8ullet/Yandex/blob/main/03_Research_data_analysis/Research_real_estate_data.ipynb)|Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир.|`Python` `NumPy` `Matplotlib` `Plotly` `math`|
|4. [Определение параметров коммерческой успешности компьютерных игр](https://github.com/kama8ullet/Yandex/blob/main/04_Game_analytics/Game_analytics.ipynb)|Необходимо выявить определяющие успешность игры закономерности, чтобы сделать ставку на потенциально популярный продукт и спланировать рекламные кампании|`Python` `Pandas` `Matplotlib` `Seaborn` `math` `warnings` `stats` `ProfileReport`|
|5. [Определение выгодного тарифа для телеком компании](https://github.com/kama8ullet/Yandex/blob/main/05_Statistical_analysis/Statistical_analysis.ipynb)|На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа.|`Python` `Pandas` `Numpy` `Matplotlib` `SciPy`|
|6. [Классификаиция клиентов телеком компании](https://github.com/kama8ullet/Yandex/blob/main/06_Machine_learning_beginning/Machine_learning_beginning.ipynb)|На основе данных мобильных операторов предложить клиенту  новый тариф. <br> Цель - построить модель для задачи классификации, которая выберет подходящий тариф.|`Python` `Pandas` `Matplotlib` `Scikit-learn`|
|7. [Прогнозирование оттока клиента Банка](https://github.com/kama8ullet/Yandex/blob/main/07_Customer_outflow/Customer_outflow.ipynb)|На основе данных из банка определить клиент, который может уйти|`Python` `Pandas` `Numpy` `Matplotlib` `Seaborn` `Scikit-learn`|
|8. [Определение наиболее выгодного региона нефтедобычи](https://github.com/kama8ullet/Yandex/blob/main/08_Machine_learning_business/Machine_learning_business.ipynb)|На основе данных геологи разведки необходимо построить модель для определения региона, где добыча нефти принесёт наибольшую прибыль.|`Python` `Pandas` `Numpy` `Matplotlib` `Seaborn` `Scikit-learn` `stats`|
|9. [Предсказание коэффициента восстановления золота из золотосодержащей руды](https://github.com/kama8ullet/Yandex/blob/main/09_Gold_recovery/Gold_recovery.ipynb)|Нужно построить модель, которая предскажет коэффициент восстановления золота из золотосодержащей руды по данным с параметрами добычи и очистки.|`Python` `Pandas` `Numpy` `Matplotlib` `Seaborn` `Scikit-learn`|
|10. [Защита данных клиентов страховой компании](https://github.com/kama8ullet/Yandex/blob/main/10_Linear_algebra/linear_algebra.ipynb)|Разработка модели анонимизации персональных данных. Обосновать корректность его работы.|`Python` `Pandas` `Numpy` `Matplotlib` `Seaborn` `Scikit-learn`|
|11. [Построение модели определения стоимости автомобиля](https://github.com/kama8ullet/Yandex/blob/main/11_Car_cost/Car_cost.ipynb)|Разработка системы рекомендации стоимости автомобиля на основе его описания.|`CatBoost` `lightgbm` `Scikit-learn` `Pandas` `NumPy` `Matplotlib` `Plotly` `math` `time`|
|12. [Прогнозирование количества заказов такси на следующий час (Временные ряды)](https://github.com/kama8ullet/Yandex/blob/main/12_Time_series/Time_series.ipynb)|Разработка системы предсказания объема заказов такси на следующий час.|`TimeSeriesSplit` `CatBoost` `lightgbm` `statsmodels` `Scikit-learn` `Pandas` `NumPy` `Matplotlib` `plotly` `math` `time`|
|13. [Обучение модели классификации комментариев (Обработка естественного языка)](https://github.com/kama8ullet/Yandex/blob/main/13_Natural_language/Natural_language.ipynb)|Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Для этого необходимо обучить модель классифицировать комментарии на позитивные и негативные.| `spacy` `SVC` `pymystem3` `re` `Scikit-learn` `Pandas` `NumPy` `Matplotlib` `plotly` `math`|
|14. [Обработка фотографий покупателя (Computer vision)](https://github.com/kama8ullet/Yandex/blob/main/14_Computer_vision/Computer_vision.ipynb)|Определение возраста по фотографии для нужд сети супермаркетов, чтобы можно было проверять добросовестность продавцов и делать целевые предложения своим покупателям. |`Keras` `TensorFlow` `Adam` `ResNet50` `ImageDataGenerator` `Seaborn` `PIL` `Pandas` `Matplotlib` `plotly` `NumPy`|
