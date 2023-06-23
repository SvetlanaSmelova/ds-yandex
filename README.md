# Примеры учебных проектов Яндекс.Практикум

|№|Название проекта|Задача проекта|Стек|
|-|:-|:-|:-:|
|1|[Исследование успешности игр в интернет-магазине](https://github.com/SvetlanaSmelova/DA_Control_project)|На основании доступных исторических данных требуется провести анализ и составить рекомендации для интернет-магазина. В ходе иссследования необходимо выявить определяющие факторы успешности игр, составить портерт пользователя для разных регионов и проверить выдвинутые гипотезы.| python, pandas, matplotlib(pyplot), numpy, scipy, seaborn|
|2|[Восстановление золота из руды]()|Подготовка прототипа модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий. По техническому заанию модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основании данных с параметрами добычи и очистки. Модель необходима для оптимизации производства, чтобы не запускать предприятие с убыточными характеристиками.|python, pandas, numpy, matplotlib, seaborn, scipy, sklearn(linear_model, tree, ensemble, dummy, preprocessing, random, model_selection, metrics, pipeline, utils)|
|3|[Прогнозирование заказов такси](https://github.com/SvetlanaSmelova/ML-for-time)|Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.|python, pandas, numpy, matplotlib(pyplot), statsmodels, sklearn(model_selection, metrics, linear_model, ensemble), catboost, lightgbm|
|4|[Проект по машинному обучению для текстов](https://github.com/SvetlanaSmelova/ML-for-text)|По заданию от интернет-магазин «Викишоп» требуется разработать модель для классификации тональности комментариев. В первую очередь магазин интересует определение токсичных комментариев для дальнейшей отправки на модерацию. Для обучения модели был получен набор данных с разметкой токсичности.|python, pandas, numpy, torch, transformers, sklearn(feature_extraction, metrics, model_selection, linear_model, ensemble), lightgbm, BERT(предобученный для определения тональности текста)|
