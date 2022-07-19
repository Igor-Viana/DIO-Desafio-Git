
# Desafio de Projeto - Uso do Git e GitHub

Esse projeto foi realizado por meio dos conhecimentos obtidos pelo curso de git e github, obtido pelos cursos da Digital Innovation One.

## Comandos Utilizados

### Manipulação de Arquivos pelo Terminal

 - **dir**: Lista todos os diretórios(pastas e arquivos) dentro da pasta atual;
 
 - **cd (nome do diretório)**: Seleciona o nome da pasta destino e entra nela;
 
 - **mkdir (nome)**: Cria uma nova pasta;

 - **rmdir (nome)**: Apaga o diretório Selecionado. 

### Comandos Git

 - **git init**: Inicia um repositório;

 - **git add**: Adiciona as Alterações feitas;

 - **git commit -m "descrição"**: Faz um commit das alterações realizadas;

 - **git push origin master**: Atualiza o repositório, enviando o commit realizado para a branch especificada ("master" nesse caso).

### Configuração de um Repositório Remoto no GitHub

 - **ssh-keygen -t ed25519 -C (e-mail)**: Cria um par de chaves SSH a serem utilizadas;

 - **eval $(ssh-agent -s)**: Inicializa o Agente SSH;

 - **ssh-add (caminho da chave privada)**: Adiciona a Chave privada gerada ao agente SSH;
 
 - **git remote add (nome do repositório) (url do repositório)**: Adiciona o repositório remoto à sua maquina;

#### Obs: Esses processos devem ser realizados após se adicionar uma nova chave SSH no github do usuário em questão. https://github.com/settings/ssh/new - Nesse caso, a chave SSH requirida é a chave pública, que possui, em seu nome, o final **.pub**.