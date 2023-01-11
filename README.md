 Weather station on AVR

The weather station is focused on monitoring temperature and humidity by means of
the *DHT11* sensor. This data will be processed by **ATtiny13**. 

# Table of content



## Construction
El sensor debe constar con una resistencia pull-up (5.1 kOhm) para que siempre este
en alto.

Como es una comuniación a un hilo (1-wire) el pin del uC se tiene que comportar
como entrada/salida al mismo tiempo (forma bidireccional). Un maestro y varios esclavos de una sola linea de datos wn la que se alimenta

La forma de comunicar es por intervalos de duración de alto de la señal
![](grafica.png)
