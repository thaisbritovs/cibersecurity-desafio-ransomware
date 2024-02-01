## Desafio: Criando um Ransomware com Python

### Criar uma pasta chamada de projeto-ransomware
    mkdir projeto-ransomware
### Acessar a pasta
     cd projeto-ransomware
    
### Criar os arquivos
    touch descrypter.py
    touch encrypter.py
    touch teste.txt
    
![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/18e27809-8e69-4149-af52-5e60cee82473)


### Acessar os arquivos e  digitar o código
### Encriptar o arquivo
    ls 
    nano encrypter
(Digitar os códigos, para salvar e retornar a tela de comandos * ^crlt O, ENTER, Crlt X)

![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/0cef14cf-e50a-49c1-9de1-775165b67539)

### Descriptografar o arquivo
    nano descrypter
(Digitar os códigos, para salvar e retornar a tela de comandos * ^crlt O, ENTER, Crlt X)

![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/8189b274-f426-4e29-9f81-6d460ef3ab79)

### No arquivo de teste escrever algo
    nano teste.txt
    
![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/ad1e71e7-a8b0-4b1c-9b3e-7a96fa00f555)


### Chegou a hora de testar a Criptografia!!!
    ls
    python encrypter
    ls
    nano teste.txt.ransowaretroll
    
![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/ae5e0979-88eb-4952-929a-47164f3bb89f)

![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/3e18d210-6b91-45b9-b221-f43af10a7797)

### Agora vamos descritografar!
    python descrypter
    ls
    nano teste.txt 

![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/41cde5a3-9db5-49d7-9058-e066ad45c74c)

![image](https://github.com/thaisbritovs/cibersecurity-desafio-ransomware/assets/154556305/eda96962-6b05-489f-b543-013b0f19d6d8)

### *Observação: Foi necessário instalar o módulo pyaes.
    pip install pyaes

    
