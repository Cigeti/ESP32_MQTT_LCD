# ESP32_Introduccion_MQTT
Programacion basica de ESP32 para MQTT con la finalidad de que los mensajen enviados se proyecten en el LCD dysplay, con la finalidad de comprender las bases de este.

## Paso 1: Pasos a seguir para usar la pagina: mqttx
- Entrar al link: http://www.emqx.io/online-mqtt-client#/recent_connections
- New connection
- Se nombra la coneccion
- Connect
- +New subscription
- Topic: Salida01: es donde se reciben datos
- Cambiar json por Plaintext
- Topic: Entrada01
## Paso 2: Descarga de librerias
- Se descarga la libreria: Wifi
- Se descarga la libreria: PubSubClient
- Se descarga la libreria: LiquidCrystal

## Contribución
Este proyecto ha sido posible gracias a la colaboración de Andrés Hernández Chaves e Ignacio Cordero Chinchilla durante la práctica supervisada del año 2023.

## Problemas o Sugerencias
Revisar el diagrama de conexiones del LCD con el ESP32
Tener cuidado con los topicos tanto el del entrada como el de salida.