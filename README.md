# Phishing para captura de senhas do Orkut

### Ferramentas

- BlackArch Linux
- setoolkit

### Configurando o Phishing no BlackArch Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Custom Import ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.orkut.com

### Encontrando o HTML

-> Decidi clonar a página do Orkut, então fui atrás do html no wayback-machine

![wayback-machine](https://github.com/user-attachments/assets/f27d6eb5-17bc-4b85-8d2c-50f082b55741)

### Tweaking

-> Tive alguns problemas com o redirecionamento ao clicar no login, porque levava para autenticar com o gmail, então simplesmente tirei

![index-tweak](https://github.com/user-attachments/assets/ff91845c-6ec6-480b-a5bd-53eb251604f6)

### Enfim, a página

-> Nostálgico?

![pagina-http](https://github.com/user-attachments/assets/d7d9d610-669f-4322-a220-0b868fd18844)

### Resultados

-> Por fim, os resultados... 

![creds](https://github.com/user-attachments/assets/dbfa33b6-a2ec-42bf-8c58-b3aa6bef81a3)
