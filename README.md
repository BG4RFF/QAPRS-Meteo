# QAPRS-Meteo
Small APRS meteo station

Программа APRS метеостанции. Измеряет и передаёт температуру, давление и влажность. Для передачи сообщений по радио и для формирования AFSK сигнала используется библиотека QAPRS - http://www.kh-gps.de/qaprs.htm.
Для измерения влажности и наружной температуры используется датчик DHT22 (библиотека для Ардуино - https://github.com/markruys/arduino-DHT). Для измерения давления и внутренней температруры - модуль из Китая на BMP180 (библиотека для Ардуино - https://github.com/adafruit/Adafruit-BMP085-Library).
