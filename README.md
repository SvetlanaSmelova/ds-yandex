# Примеры учебных проектов Яндекс.Практикум

|№|Название проекта|Задача проекта|Стек|
|-|:-|:-|:-:|
|1|Исследовательский анализ данных ["Исследование успешности игр в интернет-магазине"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/5_control_project_1)|На основании доступных исторических данных требуется провести анализ и составить рекомендации для интернет-магазина. В ходе исследования необходимо выявить определяющие факторы успешности игр, составить портрет пользователя для разных регионов и проверить выдвинутые гипотезы.| python, pandas, matplotlib(pyplot), numpy, scipy, seaborn|
|2|Машинное обучение и исследовательский анализ ["Отток клиентов банка"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/7_ml_with_teacher)|В данной работе проведено исследование оттока клиентов из «Бета-Банка». Задача данного исследования - построить модель для предсказания ухода клиента на основании предоставленных данных о клиентах.| pandas, pyplot, numpy, random, joblib, sklearn(linear_model, tree, ensemble, preprocessing, model_selection, metrics, utils)|
|3|Машинное обучение в бизнесе ["Выбор региона для разработки скважины"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/blob/main/8_ml_in_business)|Проведение исследования по выбору региона для разработки новой скважины компании «ГлавРосГосНефть». Для исследования предоставлены исторические данные по скважинам трех регионов. На основании полученных данных нужно разработать модель, определяющую регион с максимальной прибыльностью.| pandas, numpy, random, seaborn, scipy, sklearn(linear_model, random, model_selection, metrics, utils)|
|4|Машинное обучение ["Восстановление золота из руды"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/9_control_project_2)|Подготовка прототипа модели машинного обучения для золотодобывающей компании. Компания разрабатывает решения для эффективной работы промышленных предприятий. По техническому заданию модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основании данных с параметрами добычи и очистки. Модель необходима для оптимизации производства, чтобы не запускать предприятие с убыточными характеристиками.|python, pandas, numpy, matplotlib, seaborn, scipy, sklearn(linear_model, tree, ensemble, dummy, preprocessing, random, model_selection, metrics, pipeline, utils)|
|5|Линейная алгебра. Матрицы ["Защита персональных данных клиентов"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/10_Linear_algebra)|Страховой компании «Хоть потоп» требуется защитить персональные данные клиентов. Для этого компания хочет получить метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. |python, pandas, numpy, matplotlib(pyplot), sklearn(linear_model, model_selection, metrics)|
|6|Машинное обучение. Градиентный бустинг ["Определение стоимости автомобилей"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/11_ml_gradient_boost)|Сервис по продаже автомобилей с пробегом разрабатывает новое приложение. Чтобы привлечь новых клиентов планируется внедрить возможность автоматического определения стоимости автомобиля.|python, pandas, numpy, matplotlib(pyplot), statsmodels, sklearn(linear_model, ensemble, preprocessing, random, model_selection, metrics), lightgbm|
|7|Машинное обучение для временных рядов ["Прогнозирование заказов такси"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/12_ml_by_time)|Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построена модель для такого предсказания.|python, pandas, numpy, matplotlib(pyplot), time, sklearn(model_selection, metrics, linear_model, ensemble), catboost, lightgbm|
|8|Машинное обучение для классификации тональности текстов ["Проект по машинному обучению для текстов"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/13_ml_for_text)|По заданию от интернет-магазина требуется разработать модель для классификации тональности комментариев. В первую очередь магазин интересует определение токсичных комментариев для дальнейшей отправки на модерацию. Для обучения модели был получен набор данных с разметкой токсичности.|python, pandas, numpy, torch, transformers, sklearn(feature_extraction, metrics, model_selection, linear_model, ensemble), lightgbm, BERT(предобученный для определения тональности текста)|
|9|Исследовательский анализ данных и машинное обучение["Прогноз оттока клиентов"](https://github.com/SvetlanaSmelova/ds_yandex_practicum/tree/main/14_final_project)|По заданию от компании «Ниединогоразрыва.ком» требуется произвести исследование и создать модель, прогнозирующую уход клиента. В качестве исходной информации получены исторические данные компании. Результаты проведенной работы планируется использовать для удержания текущих клиентов.|pandas, matplotlib(pyplot), numpy, seaborn, datetime, phik, time, sklearn(preprocessing, model_selection, metrics, ensemble, dummy), catboost, lightgbm|
