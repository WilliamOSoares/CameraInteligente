# CameraInteligente
Algoritmo para detectar pessoas em câmeras de segurança, notificando a detecção atraves de um Broker MQTT. 

Para a simulação das câmeras ser ́a necessário fazer a instalação das bibliotecas que foram utilizadas no projeto, oTensor Flow, Opencv, Imutils, além da PAHO que foi usada na comunicação, que ser ́a descrita posteriormente. Para a instalação das bibliotecas basta digitar os seguintes comandos no Prompt de Comando(CMD):
- pip install tensorflow, para a instalação do Tensor Flow;
- pip install imutils, para a instalação do Imutils;
- pip install opencv-python, para a instalação do OpenCV;
- pip install paho-mqtt, para a instalação do PAHO

Os dados estão sendo simulados através de vídeos de câmeras de segurança, para ser aplicado ao mundo real precisará adaptar o código.

Como também, para ser executado precisará de um Broker MQTT online.
