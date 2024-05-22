# monitor-temperatura-IoT
Meu projeto IoT sera realizado em IDE Arduino.

## <br> Descrição
Uilizarei o ESP32 para controle de temperatura e utilizando um DHT11, sendo que utilizarei
uma IDE Arduino, buscando uma comunicacao via MQTT e um Adafruit.

## <br> Modelo de Montagem 

![image](/fotos/prototipo.png)

## <br> Graficos

Temperatura
![image](/fotos/temperature.png)

Dashboard
![image](/fotos/dashboardTemperatura.png)

## <br> Vídeo-demonstração

https://www.youtube.com/watch?v=W9LmVoMkpok

## <br> Dados obtidos via MQTT no Ubidots

Os dados obtidos pela MQTT, nao foram realizados devido ao problema na DHT11, esta enviando dados NAN para a MQTT, mesmo mostrando conectado, os dados estao sendo solicitados a cada 2 segundos, os dados estao sendo obtidos em fahrenheit, diante disto tem um calculo para mudar para Celcius.
