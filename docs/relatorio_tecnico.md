# Relatório Técnico – Sistema de Monitoramento e Controle de Estufa

## Introdução
Este projeto foi desenvolvido como Projeto Final do curso de Sistemas Embarcados, utilizando a plataforma Franzininho WiFi LAB01 (ESP32).

## Aplicação dos Conceitos do Curso
Durante o desenvolvimento do projeto foram aplicados conceitos de sistemas embarcados, incluindo leitura de sensores digitais e analógicos, uso do ADC do ESP32, interface com display OLED, comunicação serial, sistema de arquivos embarcado e organização modular do código em componentes.

## Diagrama de Blocos do Hardware
O sistema utiliza a Franzininho WiFi LAB01 como unidade central, conectada ao sensor DHT11 para leitura de temperatura e umidade, ao sensor LDR para leitura de luminosidade, ao display OLED via I2C para exibição das informações e a um LED ou relé para simular o controle térmico. A memória interna do ESP32 é utilizada para armazenamento dos dados monitorados, e a comunicação serial permite o acesso aos registros salvos.

## Justificativa das Escolhas Técnicas
O sensor DHT11 foi escolhido por sua simplicidade de uso e fácil integração. O LDR foi utilizado por ser uma solução de baixo custo para medição de luminosidade. O ESP-IDF foi adotado por ser o framework oficial do ESP32, oferecendo maior controle do hardware. O uso do SPIFFS ou LittleFS possibilita o armazenamento persistente dos dados monitorados.

## Conclusão
O projeto atende aos requisitos propostos no curso, demonstrando a aplicação prática dos conceitos de sistemas embarcados de forma organizada e funcional.
