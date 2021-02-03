# Projeto-MQTT [IOT]--Nadson Andrey

# Objetivo

O objetivo desse projeto é utilizar um Arduino Uno mais um Sensor Magnético para monitorar se a porta de um Rack
de Rede está ABERTO ou FECHADO; enviar essa informação via Internet utilizando o protocolo MQTT (*Message
Queuing Telemetry Transport*) para um servidor MQTT hospedado na *Amazon Web Service* (AWS) e exibir a informação
em um cliente MQTT ([MQTT Dash] (https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=en&gl=US)) instalado em um Smartphone, conforme imagem abaixo.

![Fluxograma - IOT] (https://github.com/andreyyanushik/projeto-mqtt--nadsonandrey-/blob/main/Fluxograma%20-IOT.png)


# Foram utilizadas as seguintes bibliotecas:
 * [UIPEthernet] ( https://github.com/UIPEthernet/UIPEthernet)(conexão do ENC28J60 com o Arduino)
 * [PubSubClient] (https://github.com/knolleary/pubsubclient) (cliente MQTT para o Arduino)

# Materiais
 * Arduino Uno
 * Módulo Ethernet (ENC28J60)
 * Sensor Magnético (MC-38)
 * Jumpers
 
  # Circuito
  
  ![Arduíno] (https://camo.githubusercontent.com/ad1da211b35b60b23fb095a64e76dc6504d0c3229e853bd82a69a4d5d27bbb88/68747470733a2f2f692e696d6775722e636f6d2f594947477453472e706e67)


# Autor: Nadson Andrey
[Linkedin] (https://www.linkedin.com/in/nadson-andrey-alves-da-cruz-sena-5871b3a4/)
