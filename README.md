# Padrão de Cores para Fios em Microcontroladores

Este repositório documenta um padrão de cores sugerido para fios em projetos com microcontroladores, facilitando a organização e a identificação das conexões.

📖 Leia em [English](README_EN.md).

## 📦 Estrutura de Cores

### Alimentação e Energia
- **VCC (Voltage Common Collector - +5V, +3.3V):** 🔴 Vermelho ou 🟠 Laranja
- **GND (Ground - Terra):** ⚫ Preto ou 🟤 Marrom

### Dados e Comunicação
- **GPIO (General Purpose Input/Output - Digitais):** ⚪ Branco, ⚪ Cinza ou 🔵 Azul-claro
- **I²C (Inter-Integrated Circuit):**
  - **SDA (Serial Data Line):** 🔵 Azul ou 🟢 Verde-claro
  - **SCL (Serial Clock Line):** 🟡 Amarelo ou 🟠 Laranja
- **UART (Universal Asynchronous Receiver-Transmitter):**
  - **RX (Receive):** 🟢 Verde
  - **TX (Transmit):** 🟡 Amarelo
- **SPI (Serial Peripheral Interface):**
  - **MISO (Master In Slave Out):** 🟣 Roxo
  - **MOSI (Master Out Slave In):** 🟠 Laranja
  - **SCK (Serial Clock):** 🟡 Amarelo
  - **CS/SS (Chip Select/Slave Select):** ⚪ Cinza ou 🔵 Azul-escuro

### Outras Funções
- **PWM (Pulse Width Modulation):** 🔵 Azul ou 🟣 Roxo
- **Interruptores ou Controle:** ⚪ Branco ou ⚪ Cinza

## 🎯 Boas Práticas
- **Consistência:** Use as mesmas cores para as mesmas funções em todo o projeto.
- **Documentação:** Etiquete os fios e registre as conexões.
- **Segurança:** Certifique-se de que as cores indicam corretamente a polaridade e os sinais.

## 📥 Contribuições
Sinta-se à vontade para abrir um pull request ou issue para sugestões e melhorias.

## 📜 Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](https://github.com/ferreiramateusalencar/Padroes-de-Cores-para-Fios-em-Microcontroladores/blob/main/LICENSE) para mais detalhes.

---

🎯 **Organize seu projeto com eficiência e evite confusões!**
