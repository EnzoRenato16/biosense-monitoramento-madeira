# 🌲 Biosense - Monitoramento Inteligente de Madeira

Projeto de monitoramento ambiental usando ESP32-CAM com sensor DHT22 para capturar:
- 📷 Imagens em tempo real da madeira
- 🌡️ Temperatura e 💧 umidade via sensor


## 🚀 Como usar

### 1. Back-End (ESP32-CAM)
- Abra `esp32cam_dht22_backend.ino` na Arduino IDE
- Instale as bibliotecas:
  - ESP32 Board by Espressif
  - Adafruit DHT Sensor + Unified Sensor
- Configure seu Wi-Fi (`ssid`, `password`)
- Faça o upload para a ESP32-CAM

### 2. Front-End
- Edite o IP da ESP32-CAM no `index.html` (linha `const ipESP = "http://<SEU_IP>"`)
- Abra `index.html` no navegador (ou hospede em um servidor)

## 📷 Funcionalidades
- Visual da câmera: `/cam`
- Dados em JSON: `/dados`

## 📃 Licença
MIT License


