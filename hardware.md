# Устройство датчика

Универсальная плата датчика качества воздуха, основана на ESP8266 позволяет использовать следующие модули:  NODEMCU v3, NODEMCU v2, WEMOS D1 MINI. Устройство расчитано на питание 6 - 24 вольта, при  использовании DC-DC преобразователя DC MINI560.

![plata](images/plata.png)

Данная плата позволяет подключить датчики PM:

- [SDS011](https://cdn-reichelt.de/documents/datenblatt/X200/SDS011-DATASHEET.pdf)
- PMS1003-6003
- [PMS7003/G7](http://www.plantower.com/en/content/?110.html)
- [SPS 30 PM Sensor](https://sensirion.com/products/catalog/SPS30/)

Возможность подключения по интерфейсу I2C :

- [BMP180](https://cdn-shop.adafruit.com/datasheets/BST-BMP180-DS000-09.pdf) - температура и влажность
- [BME/P280](https://www.mouser.com/datasheet/2/783/BST-BME280-DS002-1509607.pdf) - температура, влажность, атмосферное давление
- [HTU21D](https://eu.mouser.com/ProductDetail/Measurement-Specialties/HTU21D?qs=tx5doIiTu8oixw1WN5Uy8A%3D%3D) - температура и влажность
- SHT3x (I2C) - температура и влажность
- [CCS811 VOC SENSOR](https://www.sciosense.com/wp-content/uploads/documents/Application-Note-Baseline-Save-and-Restore-on-CCS811.pdf) - Летучие органические вещества, еквивалент СО2
- LCD1602/ 2004 / OLED SSD1306 /  SH1106 - поддерживаемые дисплеи

Возможность подключения по интерфейсу 1 Wire :

- DTH22(AM2302) - температура и влажность
- DS18B20 - температура.

Также существует модель MINI уменьшенного размера и с урезанным списком подключаемых устройств. Исходные схемы для обеих моделей можно найти по ссылкам для [полной модели](https://oshwlab.com/ludovich88/aira_sensor_rev0-1) и [модели MINI](https://oshwlab.com/ludovich88/aira_sensor_d1_mini).

> Чтобы получить готовую плату, свяжитесь с разработчиками по адресу vm@multi-agent.io.


