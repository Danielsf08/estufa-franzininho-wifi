estufa-franzininho-wifi

# Sistema de Monitoramento e Controle de Estufa – Franzininho WiFi LAB01

## Descrição do Projeto
Este projeto implementa um sistema embarcado para monitoramento e controle de uma estufa utilizando a Franzininho WiFi LAB01 (ESP32) e o ESP-IDF. O sistema monitora temperatura, umidade e luminosidade, exibindo os dados em um display OLED, permitindo a configuração de um set point de temperatura por meio de um menu interativo e o registro dos dados em memória interna.

## Hardware Utilizado
- Franzininho WiFi LAB01 (ESP32)
- Sensor DHT11
- Sensor LDR
- Display OLED (I2C)
- Resistores
- LED ou relé

## Software Utilizado
- ESP-IDF
- SPIFFS ou LittleFS
- Terminal serial

## Estrutura do Projeto
project-root/
main/
components/
docs/

## Instalação e Configuração
1. Configurar o ambiente ESP-IDF.
2. Clonar o repositório.
3. Executar idf.py menuconfig.
4. Compilar e gravar com idf.py build flash monitor.

## Uso do Sistema
- O display OLED mostra temperatura, umidade e lumi
