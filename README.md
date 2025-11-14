## 1.1 Informações Técnicas da Placa Arduino UNO R3

O projeto foi desenvolvido utilizando a placa **Arduino UNO Rev3**, uma das plataformas mais utilizadas em projetos educacionais, protótipos eletrônicos e aplicações de automação. O Arduino UNO é baseado no microcontrolador **ATmega328P** e foi escolhido por sua facilidade de uso, compatibilidade com diversos sensores e vasta documentação disponível.

### 1.2 Características Gerais da Placa

- Microcontrolador: ATmega328P  
- Tensão de operação: 5V  
- Tensão recomendada de entrada (alimentação externa): 7–12V  
- Número de pinos digitais: 14 (sendo 6 com saída PWM)  
- Entradas analógicas: 6  
- Clock: 16 MHz  
- Memória Flash: 32 KB (0,5 KB utilizados pelo bootloader)  
- SRAM: 2 KB  
- EEPROM: 1 KB  
- Conexões: USB-B, pino VIN, conector ICSP e entrada de alimentação DC  
- Peso aproximado: 25 g  

O Arduino UNO contém tudo o que é necessário para operar o microcontrolador, bastando conectá-lo ao computador via USB ou alimentá-lo externamente. A placa possui também um **reset automático**, facilitando o envio de código sem a necessidade de pressionar o botão físico.

### 1.3 Entradas e Saídas

- **Pinos digitais (0–13):** podem ser configurados como entrada ou saída.  
- **Pinos PWM (3, 5, 6, 9, 10, 11):** permitem controle de intensidade luminosa, velocidade de motores, entre outros.  
- **Pinos analógicos (A0–A5):** leitura de valores variáveis, como sensores analógicos.  
- **Pino 13:** possui um LED embutido útil para testes.

### 1.4 Alimentação

A placa pode ser alimentada de duas formas:

- **Via USB** (5V)  
- **Via fonte externa**, com tensão entre **7 e 12V** (recomendado)

Quando alimentada externamente acima de 12V, o regulador pode superaquecer. Valores abaixo de 7V podem causar instabilidade durante o funcionamento.

### 1.5 Comunicação

A placa suporta diferentes formas de comunicação:

- **UART (Serial):** pinos 0 (RX) e 1 (TX)  
- **I2C (TWI):** pinos A4 (SDA) e A5 (SCL)  
- **SPI:** pinos 10 (SS), 11 (MOSI), 12 (MISO), 13 (SCK)

A comunicação USB é realizada pelo chip **ATmega16U2**, que atua como conversor USB-Serial.

### 1.6 Razões para Escolha da Placa no Projeto

O Arduino UNO foi escolhido para este sistema de irrigação automática por oferecer:

- Baixa complexidade de programação  
- Facilidade de conexão com sensores e módulos  
- Importante capacidade de expansão  
- Custo acessível  
- Alta durabilidade e estabilidade  
- Grande quantidade de exemplos, tutoriais e documentação

Essas características tornam o Arduino UNO ideal para projetos acadêmicos e protótipos funcionais.

---

