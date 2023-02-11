  Neste simples projeto eu mostro o quão fácil pode ser criar um link de phishing, para roubar credenciais de pessoas desavisadas a partir do Kali Linux.
  
No terminal do Kali, começo com o comando *sudo su* para utilizar o terminal como um usuário root:
  
![comando_sudo](https://user-images.githubusercontent.com/100307346/218281197-f2b52d5d-c8b6-4b5d-9b15-79cf8207a820.png)


Em seguida utilizo a ferramenta setoolkit. Uma ferramenta utilizada para ataques de engenharia social que ja vem instalada previamente no Kali. Pode ser chamada com o comando *setoolkit*, logo após, abrindo uma interface com varias opções:

![options](https://user-images.githubusercontent.com/100307346/218282215-536701a4-6ede-42b2-9434-9815d1229294.png)


Após a escolha da PRIMEIRA opção de ataques de engenharia social aparecerão as seguintes opções:

![options2](https://user-images.githubusercontent.com/100307346/218282216-e6e36e5a-0210-434d-b3f3-117bab33faba.png)


Após a escolha da SEGUNDA opção de usar sites como vetores de ataque aparecerão as seguintes opções:

![options3](https://user-images.githubusercontent.com/100307346/218282213-9776b722-2046-4b03-9a12-25c5d49228a7.png)


Após a escolha da TERCEIRA opção que será um método de coleta de dados, aparecerão as seguintes opções:
 
![options4](https://user-images.githubusercontent.com/100307346/218282361-45c93ed1-ce21-4d7c-9105-08679d29edb5.png)

Feito a escolha da SEGUNDA opção, você escolherá o IP que será inserido a clonagem de algum outro site. Depois, você irá inserir a URL do site que você pretende fazer a coleta.
Este método de ataque se aproveita de páginas de login, logo, o mais adequado é clonar uma pagina de login de sites terceiros.

![alvo](https://user-images.githubusercontent.com/100307346/218282641-c7c9348c-2a33-48e0-9b3f-dc3f161b1c6d.png)

Site clonado:
![site_clone](https://user-images.githubusercontent.com/100307346/218282888-a2c009e3-31d1-4d65-8c90-e4d15d9f70c1.png)


Ao inserir as credenciais e clicar no botão de login, elas aparecerão no terminal do Kali Linux. Depois do processo do falso login, o site irá redireciona-lo ao site original. Se as credencias estiverem corretas, o usuário será logado em sua conta sem suspeitar de nada.

Terminal com as credenciais roubadas:

![credenciais](https://user-images.githubusercontent.com/100307346/218283064-47bca6ee-01ec-41b6-8d93-b3c6023c39d9.png)



Conclusão, após esse processo foi possivel ver o quão simples pode ser criar um site malicioso, portanto SEMPRE TOME CUIDADO COM LINKS SUSPEITOS.
