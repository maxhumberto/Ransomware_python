# Ransomware_python


 Como Executar
1. Criar o arquivo de teste
bash
Copiar
Editar
mkdir test_files
echo "Este é um exemplo de conteúdo." > test_files/teste.txt
2. Rodar o encriptador
bash
Copiar
Editar
python encrypter.py
Isso irá:

Ler o teste.txt

Criptografar usando AES CTR

Criar o arquivo teste.txt.ransomwaretroll

Deletar o original

3. Rodar o decriptador
bash
Copiar
Editar
python decrypter.py
Isso irá:

Ler o teste.txt.ransomwaretroll

Descriptografar com a mesma chave

Restaurar o teste.txt

🔐 Chave de Criptografia
A chave utilizada é definida no código:

python
Copiar
Editar
key = b"testeransomwares"
Para segurança real, recomenda-se:

Geração randômica

Armazenamento seguro

📘 Aprendizados
Criptografia simétrica com pyaes

Manipulação de arquivos com Python

Boas práticas de segurança em simulações

Controle de fluxo de encriptação/desencriptação

⚠️ Aviso Legal
Este projeto é somente para aprendizado. Usar técnicas semelhantes fora de ambientes autorizados pode ser crime, conforme o Art. 154-A do Código Penal Brasileiro.

👨‍💻 Autor
Humberto da Silva Lucas
Projeto educacional para estudos em Python e segurança da informação.

