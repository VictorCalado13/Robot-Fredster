# 🤖 Fredster - Robô Explorador

Fredster é um robô explorador controlado via gamepad, desenvolvido com Arduino Nano e módulos de baixo custo. O projeto utiliza o aplicativo **Dabble** para enviar comandos ao robô, permitindo uma interface de controle intuitiva por Bluetooth.

---

## **🚀 Descrição**

O Fredster foi criado para demonstrar um sistema de robótica móvel simples, controlado remotamente, com capacidade de exploração e deslocamento em ambientes variados. Ele utiliza o módulo Dabble para facilitar a comunicação via Bluetooth com o celular, e movimenta-se através de dois motores DC controlados por uma ponte H.

---

## **🛠️ Tecnologias e Componentes**

- **Arduino Nano V3**
- **Bluetooth HM-10**
- **Ponte H L9110S**
- **2 motores DC 12V**
- **Aplicativo Dabble (Gamepad Module)**

---

## **📦 Bibliotecas Necessárias**

Para que o aplicativo Dabble funcione corretamente com o robô Fredster, é necessário incluir estas bibliotecas no seu código Arduino:
```plaintext
#define CUSTOM_SETTINGS
#define INCLUDE_GAMEPAD_MODULE
#include <Dabble.h>

