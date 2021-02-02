# * ENTREGAVEL - SPRINT 8.MD*
## *OBJETIVO*

O objetivo dessse projeto é utilizar um Arduino Uno mais um Sensor Magnetco para monitorar se a porta de um Rack de Rede esta *ABERTA* ou se ela esta *FECHADA* ;enviar essa informação via Internet utilizando p protocolo MQTT(**Message Queuing Telemetry Transport**)para um sservidor MQTT ospedado na **Amazon Web ervice**(AWS)e exibir a informação em um cliente [*MQTT*](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=en&gl=US)instalado em um  Smartphone.   

* Foram utilizadas as seguintes bibliotecas:

  * UIPEthernet (conexão do ENC28J60 com o Arduino)
  * PubSubClient (cliente MQTT para o Arduino)

### *MATERIAIS ULTILIZADOS*

 * Arduino Uno
 * Môdulo Ethernet(ENC28J60)
 * Sensor Magnético(MC-38)
 * Jumpers
