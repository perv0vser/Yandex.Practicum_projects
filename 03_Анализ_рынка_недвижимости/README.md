# Анализ рынка недвижимости


## Данные

В нашем распоряжении данные онлайн сервиса по продаже недвижимости — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет:
* расстояние до ближайшего аэропорта в метрах (м)
* число балконов
* высота потолков (м)
* расстояние до центра города (м)
* сколько дней было размещено объявление (от публикации до снятия)
* дата публикации
* этаж
* всего этажей в доме
* апартаменты (булев тип)
* площадь кухни в квадратных метрах (м²)
* цена на момент снятия с публикации
* жилая площадь в квадратных метрах (м²)
* название населённого пункта
* свободная планировка (булев тип)
* число парков в радиусе 3 км
* расстояние до ближайшего парка (м)
* число водоёмов в радиусе 3 км
* расстояние до ближайшего водоёма (м)
* число комнат
* квартира-студия (булев тип)
* площадь квартиры в квадратных метрах (м²)
* число фотографий квартиры в объявлении

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

## Задача

Нужно научиться определять рыночную стоимость объектов недвижимости. Задача проекта — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

## Теги
`Python`, `Pandas`, `Seaborn`, `Matplotlib`
