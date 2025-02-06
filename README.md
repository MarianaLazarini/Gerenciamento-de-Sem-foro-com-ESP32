# 🚦 Sistema Inteligente de Semáforos com ESP32

Este projeto implementa um sistema de semáforos inteligentes utilizando ESP32 e comunicação MQTT. O sistema permite a configuração dinâmica do tempo dos semáforos, suporta até quatro unidades semafóricas e possibilita o monitoramento e controle em tempo real via MQTT.

📃 O projeto foi originalmente escrito por outro grupo, porém em um sorteio, foi designado para mim e minha dupla implementarmos exatamente o que foi escrito. Durante o processo, seguimos fielmente a lógica proposta, adaptando o código para garantir que a funcionalidade planejada fosse atingida com os componentes e hardware disponíveis.

📌 Funcionalidades:
- Configuração do número de semáforos (2 a 4);
- Ajuste do tempo de cada fase (verde, amarelo e vermelho);
- Modo de configuração manual via botão;
- Integração com MQTT para monitoramento remoto;
- Sensores para gestão adaptativa do tráfego.

🛠️ Hardware Utilizado:
- ESP32 (microcontrolador principal);
- Semáforos com LEDs indicadores (Verde, Amarelo, Vermelho);
- Botões físicos para ajuste de parâmetros;
- Sensores para detecção de tráfego;
- Broker MQTT para comunicação remota.

🚀 Como Utilizar:
- Ligue o ESP32 e conecte ao broker MQTT;
- Entre no modo de configuração usando o botão;
- Ajuste os parâmetros (tempo dos sinais, número de semáforos);
- Execute o sistema, que funcionará dinamicamente conforme o tráfego.
