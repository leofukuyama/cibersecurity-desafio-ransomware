# Script para criptografar e descriptografar arquivos .txt em Python

### Ferramentas

- Kali Linux
- Python (Bibliotecas ``` os ``` e ``` pyaes ```)

### Configurando o projeto

- Criar diretório: ``` mkdir projeto-ransomware ```
- Acessar diretório: ``` cd projeto-ransomware ```
- Criar arquivos: ``` touch encrypter.py ```
                  ``` touch decrypter.py ```
                  ``` touch teste.txt ```

### Lógica do encrypter.py

- Acessar o arquivo;
- Definir bibliotecas;
- Abrir o arquivo a ser criptografado.;
- Remover o arquivo original;
- Criar uma chave de criptografia de 16 caracteres para bits;
- Criptografar o arquivo;
- Salvar um arquivo novo criptografado.

### Lógica do decrypter.py

- Acessar o arquivo;
- Definir bibliotecas;
- Abrir o arquivo criptografado;
- Fornecer a chave para descriptografia;
- Remover o arquivo criptografado;
- Salvar um arquivo novo descriptografado.

### Resultados

- É possível criptografar e descriptografar arquivos .txt com qualquer chave de 16 caracteres.
