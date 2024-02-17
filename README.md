# ML.Feature Selection
## Исследование данных об подержаных автомобилях марки Ford.
## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Провести разведовательный анализ данных и статистические тесты.

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
1. Базовый анализ структуры данных.
2. Создание модели на основе признаков без отбора и проверка метрики MAE.
3. Создание модели на основе признаков с их отбором с помощью RFE и провека метрики MAE.
4. Создание модели на основе признаков с их отбором с помощью SelectKBest и проверка метрики MAE.
5. Сверка метрик и вывод качательно проведённых действий.

**Условия соревнования:**  


**Метрика качества**     
MAE

**Что практикуем**     
Селекция признаков на основе RFE и SelectKBest.


### Краткая информация о данных
В данных представлена информация о параметрах авто, ценах, местоположении и годе выпуска.
  
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы над проектом 
1. Постановка задачи.
2. Просмотр данных из таблицы.
3. Построение и проверка модели на дэфолтных признаках (не всех).
4. Построение модели на признаках, отобраннх с помощью RFE.
5. Построение модели на признаках, отобранных с помощью SelectKBest.
6. Сверка метрик.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Если выбирать модель конкретно после использования методов секеции, то лучший результат у модели с использованием SelectKbest.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
В данном датасете отбор признаков не показал более лучший результат, чем на изначальной модели без отбора.
