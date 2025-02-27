# Projeto Final MQTT Pico W
Este projeto utiliza o Raspberry Pi Pico W com o protocolo MQTT para comunicação entre dispositivos IoT, permitindo a troca de dados em tempo real com eficiência.

Tecnologias Usadas
Raspberry Pi Pico W
MQTT (Protocolo de mensagens)
Pico SDK (C/C++)
Wi-Fi para comunicação de rede
Como Executar
Clone o Repositório:

git clone https://github.com/AtilaGoesSk/ProjetoFinalMqttPicoW.git
Configuração do Ambiente:

Instale o Pico SDK em sua máquina seguindo este guia oficial.
Configure a ferramenta de build para o Pico W e o SDK de acordo com a documentação.
Configuração do MQTT:

Crie uma conta em uma plataforma de broker MQTT (por exemplo, HiveMQ) ou configure seu próprio broker MQTT.
No código fonte, altere as credenciais do broker MQTT, incluindo o IP e a porta de conexão.
Compilar e Enviar o Código:

Compile o código no ambiente de desenvolvimento do Pico SDK:

mkdir build
cd build
cmake ..
make
Carregue o firmware no Raspberry Pi Pico W utilizando a ferramenta de upload do Pico.
Conecte à Rede Wi-Fi:

No código, insira as credenciais de sua rede Wi-Fi para que o Pico W se conecte à internet.
Execute a Comunicação MQTT:

Ao executar o código, o Pico W irá se conectar ao broker MQTT configurado e poderá enviar/receber mensagens.
Exemplos de Uso
O dispositivo pode publicar dados de sensores e receber comandos.
Use ferramentas como MQTT Explorer para visualizar as mensagens publicadas e assinadas no broker.
Licença
Este projeto está licenciado sob a Licença MIT.
