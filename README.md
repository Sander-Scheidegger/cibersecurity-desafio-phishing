# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Alt text](./clone-facebook.png "Pagina clone do Facebook")
![Alt text](./captura-facebook.png "POST capturado")

## Foi possível realizar a captura, porém os dados estavam encriptados (embora a página clonada utilizasse protocolo HTTP).

## Tentativa com um site alternativo (Spotify).

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://accounts.spotify.com/pt-BR/login

### Resultados

![Alt text](./clone-spotify.png "Pagina clone do Spotify")
![Alt text](./captura-spotify.png "POST capturado")
