# Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости

## Данные

В наличии были следующие данные:

### Таблица real_estate_data — информация о характеристиках недвижимости:

#### Признаки

    airports_nearest — расстояние до ближайшего аэропорта в метрах (м)

    balcony — число балконов

    ceiling_height — высота потолков (м)

    cityCenters_nearest — расстояние до центра города (м)

    days_exposition — сколько дней было размещено объявление (от публикации до снятия)

    first_day_exposition — дата публикации

    floor — этаж

    floors_total — всего этажей в доме

    is_apartment — апартаменты (булев тип)

    kitchen_area — площадь кухни в квадратных метрах (м²)

    last_price — цена на момент снятия с публикации

    living_area — жилая площадь в квадратных метрах (м²)

    locality_name — название населённого пункта

    open_plan — свободная планировка (булев тип)

    parks_around3000 — число парков в радиусе 3 км

    parks_nearest — расстояние до ближайшего парка (м)

    ponds_around3000 — число водоёмов в радиусе 3 км

    ponds_nearest — расстояние до ближайшего водоёма (м)

    rooms — число комнат

    studio — квартира-студия (булев тип)

    total_area — общая площадь квартиры в квадратных метрах (м²)

    total_images — число фотографий квартиры в объявлении



## Задача

Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир

## Используемые библиотеки и навыки


*Python*

*Pandas*

*Matplotlib*

*Исследовательский анализ данных*

*Визуализация данных*

*Предобработка данных*

## Вывод 

В данном проекте была проведена большая работа по предобработке данных (удаление дупликатов, аномальных значений, заполнение пропусков, приведение данных к одному типу, приведение текстовых значений к одному формату). Были сделаны различные выводы по изучению распределения признаков. Оказалось, что больше всего обьявлений выставлено из 5-ти и 9-ми этажных домов а также, что центр города заканчивается на 3км, так как цена резко идет на спад при этом значении.
