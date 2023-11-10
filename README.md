<h1 align="center"> Dispositivo para gerenciamento de temperatura </h1>


## ⌨ Descrição  

Nossa plataforma unificada oferece um espaço de interação e aprendizado para agricultores urbanos, ao mesmo tempo em que facilita o acesso dos consumidores aos produtos locais frescos.

## 🗃 Funcionalidades
* <b>Monitoramento de temperatura e umidade</b>: Usando um sensor DHT11 a temperatura do ambiente seria medida a todo momento para verificar se o local está apto para o trabalho e cultivo ou não(em média 23ºC), e caso a temperatura varie muito um led seria ativado para alertar que o ambiente está impróprio para conserva.


 ## 🔗 Tecnologias utilizadas
 * Linguagem de programação C;
 * Wokwi;
 * ArduinoIDE;
 * Node-red;
 * HiveMQ;

 ## ⚙ Instruções
 * Abra o simulador Wokwi e carregue o arquivo diagram.json e o arquivo sketch.ino
 * Inicie o projeto
 * Caso não tenha node-red instalado na máquina:
   * Faça a instalação do Node.js
   * Abra o cmd e digite npm install -g --unsafe-perm node-red
 *  Digite no cmd: node-red
 *  Acesse: http://localhost:1880
 *  Importe o arquivo flows.json no node-red
 *  Configure os nodes para sua preferência de conexões
 *  Abra o https://www.hivemq.com/demos/websocket-client/
 *  Se inscreva no tópico que configurou no mqtt in do node-red
 *  Veja as informações do simulador sendo mostradas no HiveMq
 *  Ou abra a dashboard do node-red e veja as informações lá
  


 ## ⚙ Ver o projeto
 Para ver o projeto entre neste link:
 https://youtu.be/ZAnLSahXkT0
