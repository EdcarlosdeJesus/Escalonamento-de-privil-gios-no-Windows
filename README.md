# Capturando dados da rede

## :beginner:INTRODUÇÃO
 Nessa etapa vamos usar o Wireshark sendo um analisador de protocolo de rede ou um aplicativo que captura pacotes de uma conexão de rede.

wireshark é um sniffer de rede, lê pacotes de dados que atravessam a rede dentro da camada TCP/IP (Transmission Control Protocol/Internet Protocol)

### Ferramentas  :hammer_and_wrench:

- Kali Linux :desktop_computer:
- Wireshark  :shark:
- DVWA :warning:


### :arrow_right:Iniciando

- Acessando o kali , DVWA e WIRESHARK
  
![image](https://github.com/user-attachments/assets/70ae99ea-481a-48f2-b4cf-228c37803a92)

 


---

 O comando ```http.request.method=="POST"``` é usado como um filtro no de exibição para isolar e visualizar apenas os pacotes de solicitação ```HTTP``` do tipo ```POST```.

Este filtro específico filtra os pacotes de rede para mostrar apenas aqueles que utilizam o método ```HTTP POST```. 

O método ```POST``` é comumente usado para enviar dados de formulários, como informações de login ou uploads de arquivos não criptografados, como podemos observar na figura abaixo.

![image](https://github.com/user-attachments/assets/578237ed-0667-4201-a852-6cfb6a06dcd4)


---

Podemos usar o IP do alvo para fazer uma filtragem e analisar os pacotes .

![image](https://github.com/user-attachments/assets/5bc0c2b9-09b9-4736-a29c-dd60b13f1491)















