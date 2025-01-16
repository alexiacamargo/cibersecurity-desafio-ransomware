# Desafio Ransomware - Encryptor e Decryptor

Este projeto contém scripts para criptografar e descriptografar arquivos usando a biblioteca **pyaes** e um algoritmo de cifra simétrica **AES (Advanced Encryption Standard)**.

## Funcionalidades

**Encryptor**: Criptografa um arquivo de entrada, transformando-o em um formato que não pode ser lido sem a chave de descriptografia.


**Decryptor**: Descriptografa o arquivo criptografado, revertendo o processo de cifragem e retornando o conteúdo original.

## Requisitos

Para rodar os scripts de criptografia e descriptografia, é necessário ter o Python instalado em sua máquina.

### Dependências

Este projeto utiliza a biblioteca **pyaes** para realizar a criptografia e descriptografia de arquivos. 

 Para instalar a biblioteca, execute:
```
pip install pyaes 
```


### Como Usar
### 1. Criptografar um Arquivo
Para criptografar um arquivo, siga os passos abaixo:

Abra o arquivo **encryptor.py** no seu editor de código preferido.
Certifique-se de que o arquivo que deseja criptografar ("teste.txt") está no mesmo diretório do script.

Execute o script:
```
python encryptor.py
```

O arquivo criptografado será salvo com a extensão **.ransomwaretroll.**

### 2. Descriptografar um Arquivo
Abra o arquivo **decryptor.py**, certifique-se de que o arquivo criptografado ("teste.txt.ransomwaretroll") esteja no mesmo diretório do script.

Execute o script:
```
python decryptor.py
```

O arquivo descriptografado será salvo com o nome original, **"teste.txt".**
