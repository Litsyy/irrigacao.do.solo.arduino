## 1.1 Informações Técnicas da Placa Arduino UNO R3
O projeto foi desenvolvido utilizando a placa **Arduino UNO Rev3**, uma das plataformas mais utilizadas em projetos educacionais, protótipos eletrônicos e aplicações de automação. O Arduino UNO é baseado no microcontrolador **ATmega328P** e foi escolhido por sua facilidade de uso, compatibilidade com diversos sensores e vasta documentação disponível.

## 1.2 Características Gerais da Placa
- **Microcontrolador:** ATmega328P  
- **Tensão de operação:** 5V  
- **Tensão recomendada de entrada (alimentação externa):** 7–12V  
- **Número de pinos digitais:** 14 (sendo 6 com saída PWM)  
- **Entradas analógicas:** 6  
- **Clock:** 16 MHz  
- **Memória Flash:** 32 KB (0,5 KB utilizados pelo bootloader)  
- **SRAM:** 2 KB  
- **EEPROM:** 1 KB  
- **Conexões:** USB-B, pino VIN, conector ICSP e entrada de alimentação DC  
- **Peso aproximado:** 25 g  

### Materiais utilizados no projeto
- Placa **Arduino Uno**  
- **Sensor de umidade**  
- **Jumpers**  
- **Protoboard**  
- **Bateria 9V**  
- **Regulador de tensão**

O Arduino UNO contém tudo o que é necessário para operar o microcontrolador, bastando conectá-lo ao computador via USB ou alimentá-lo externamente. A placa possui também um **reset automático**, facilitando o envio de código sem a necessidade de pressionar o botão físico.

## 1.3 Entradas e Saídas
- **Pinos digitais (0–13):** podem ser configurados como entrada ou saída  
- **Pinos PWM (3, 5, 6, 9, 10, 11):** permitem controle de intensidade luminosa e velocidade de motores  
- **Pinos analógicos (A0–A5):** permitem leitura de sensores analógicos  
- **Pino 13:** possui um LED integrado usado para testes

## 1.4 Alimentação
A placa pode ser alimentada de duas formas:
- **Via USB** (5V)  
- **Via fonte externa** (7–12V recomendados)

> ⚠️ Alimentação acima de 12V pode causar superaquecimento do regulador.  
> ⚠️ Abaixo de 7V pode causar instabilidade.

## 1.5 Comunicação
O Arduino UNO suporta diversos protocolos de comunicação:

- **UART (Serial):** pinos 0 (RX) e 1 (TX)  
- **I2C (TWI):** pinos A4 (SDA) e A5 (SCL)  
- **SPI:** pinos 10 (SS), 11 (MOSI), 12 (MISO), 13 (SCK)

A comunicação USB é realizada através do chip **ATmega16U2**, responsável por converter USB-Serial.

## 1.6 Razões para Escolha da Placa no Projeto
O Arduino UNO foi escolhido para o sistema de irrigação automática devido a:

- Baixa complexidade de programação  
- Facilidade de conexão com sensores e módulos  
- Alta capacidade de expansão  
- Custo acessível  
- Durabilidade e estabilidade  
- Grande quantidade de exemplos, tutoriais e documentação disponíveis

Essas características tornam o Arduino UNO ideal para projetos acadêmicos e protótipos funcionais.
---

## Resultado:

https://github.com/user-attachments/assets/7ea336f7-de9c-4887-8882-eded624d5cf8



https://github.com/user-attachments/assets/9f09539a-d089-4c6d-b4ea-c0473201dd97

