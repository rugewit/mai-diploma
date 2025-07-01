# mai-diploma

<h2>Разработка модели машинного обучения для изучения влияния различных погодных факторов на урожайность сельхоз культур</h2>

Столбы датасета содержат следующие данные.

\-    Date – данные в формате год-месяц-день-час

\-    Temperature (2 m) - Температура (2 м)

\-    Relative Humidity (2 m) - Относительная влажность (2 м)

\-    Dewpoint (2 m) - Точка росы (2 м)

\-    Apparent Temperature - Ощущаемая температура

\-    Precipitation (rain + snow) - Осадки (дождь + снег)

\-    Rain - Дождь

\-    Snowfall - Снегопад

\-    Snow depth - Высота снежного покрова

\-    Weather code - Код погоды

\-    Sealevel Pressure - Давление на уровне моря

\-    Surface Pressure - Приземное давление

\-    Cloud cover Total - Общая облачность

\-    Cloud cover Low - Нижняя облачность

\-    Cloud cover Mid - Средняя облачность

\-    Cloud cover High - Верхняя облачность

\-    Reference Evapotranspiration (ET₀) - Эталонная эвапотранспирация (ET₀)

\-    Vapour Pressure Deficit - Дефицит давления водяного пара

\-    Wind Speed (10 m) - Скорость ветра (10 м)

\-    Wind Speed (100 m) - Скорость ветра (100 м)

\-    Wind Direction (10 m) - Направление ветра (10 м)

\-    Wind Direction (100 m) - Направление ветра (100 м)

\-    Wind Gusts (10 m) - Порывы ветра (10 м)

\-    Soil Temperature (0-7 cm) - Температура почвы (0-7 см)

\-    Soil Temperature (7-28 cm) - Температура почвы (7-28 см)

\-    Soil Temperature (28-100 cm) - Температура почвы (28-100 см)

\-    Soil Temperature (100-255 cm) - Температура почвы (100-255 см)

\-    Soil Moisture (0-7 cm) - Влажность почвы (0-7 см)

\-    Soil Moisture (7-28 cm) - Влажность почвы (7-28 см)

\-    Soil Moisture (28-100 cm) - Влажность почвы (28-100 см)

\-    Soil Moisture (100-255 cm) - Влажность почвы (100-255 см)

\-    Weather code - код погоды

\-    Maximum Temperature (2 m) - максимальная температура (2 м)

\-    Minimum Temperature (2 m) - минимальная температура (2 м)

\-    Mean Temperature (2 m) - средняя температура (2 м)

\-    Maximum Apparent Temperature (2 m) - максимальная ощущаемая температура (2 м)

\-    Minimum Apparent Temperature (2 m) - минимальная ощущаемая температура (2 м)

\-    Mean Apparent Temperature (2 m) - средняя ощущаемая температура (2 м)

\-    Sunrise - восход солнца

\-    Sunset - закат солнца

\-    Daylight Duration - продолжительность светового дня

\-    Sunshine Duration - продолжительность солнечного сияния

\-    Precipitation Sum - сумма осадков

\-    Rain Sum - сумма дождя

\-    Snowfall Sum - сумма снегопада

\-    Precipitation Hours - количество часов с осадками

\-    Maximum Wind Speed (10 m) - максимальная скорость ветра (10 м)

\-    Maximum Wind Gusts (10 m) - максимальные порывы ветра (10 м)

\-    Dominant Wind Direction (10 m) - преобладающее направление ветра (10 м)

\-    Shortwave Radiation Sum - сумма коротковолновой радиации

\-    Reference Evapotranspiration (ET₀) - эталонная эвапотранспирация (ET₀)

\-    Вид культуры

\-    Наименование сорта

\-    Репродукция

\-    Номер поля

\-    Площадь

\-    Предшественник

\-    Норма высева кг/га

\-    Способ основной обработки

\-    Начало срока сева

\-    Конец срока сева

\-    Валовый сбор кг

\-    Урожайность ц\га на уборочную площадь

\-    NDVI - Нормализованный индекс разности растительности

\-    NDMI - Нормализованный индекс разности влажности

\-    NDWI - Нормализованный индекс разности вод

\-    NDSI - Нормализованный индекс разницы снега

\-    THERMAL - Тепловой диапазон 10

Карта корреляций

![](https://github.com/rugewit/mai-diploma/blob/main/1.png)

Алгоритм

![](https://github.com/rugewit/mai-diploma/blob/main/2.jpg)

Результаты обучения моделей

![](https://github.com/rugewit/mai-diploma/blob/main/3.png)

![](https://github.com/rugewit/mai-diploma/blob/main/4.png)

SHAP анализ

![](https://github.com/rugewit/mai-diploma/blob/main/5.png)

![](https://github.com/rugewit/mai-diploma/blob/main/6.png)

