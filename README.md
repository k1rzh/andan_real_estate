# andan_real_estate
![gif](https://i.gifer.com/pXx.gif)
Наш проект представляет собой многофакторный анализ рынка недвижимости в Москве с целью построения модели, призванной предсказывать цены на квартиры в зависимости от определенных критериев.  

Для того, чтобы наш анализ был всеобъемлющим, мы спарсили данные о рынке недвижимости с сайта [cian.ru](https://www.cian.ru), заполучив информацию о 1371 квартире, находящейся в продаже на май 2024 года.  

Мы рассмотрели следующие факторы, потенциально оказывающие влияние на цену квартиры: количество комнат (от 1 до 3), этаж квартиры, этажность дома, площадь квартиры, цена, расстояние до ближайшей станции метро в минутах ходьбы, ближайшая станция метро, административный округ и район Москвы.  

В ходе нашей работы мы использовали множество различных методов анализа и визуализации данных, позволивших нам построить модель, состояющую только из релевантных факторов, в действительности имеющих влияние на цену квартиры. Ниже представляем вам структуру [нашего проекта](EDA_и_обучение_модели.ipynb), которая отчетливо выделяет этапы, через которые мы должны были пройти для обучения модели по предсказанию цены квартиры:  
### 1) Сбор и последующая обработка данных  
На данном этапе мы определили нужные нам параметры, спарсили данные с Циана (которые можно найти [тут](dataset_cian_itog.csv), а также  [тут](Парсинг.ipynb)), и выяснили корреляционную зависимость факторов и их значение для нашей модели.
### 2) Проверка гипотез о зависимости цены квартиры от различных факторов
На этом этапе мы проверили четыре гипотезы, что позволило нам определиться с факторами, имеющими наибольшее значение в нашей модели.
### 3) Подготовка данных и обучение модели
На данном этапе мы провели финальную обработку данных, исключив выбросы. Затем мы определили признаки и целевую переменную и разделили выборку на тестовую и обучающую, перейдя после этого непосредственно к обучению модели.



