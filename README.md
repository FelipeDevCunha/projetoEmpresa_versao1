🚀 Funcionalidades Implementadas

Formulário de cadastro de pessoas

Envio de dados via método POST

Processamento backend em PHP

Inserção de dados no banco MySQL

Tratamento básico contra SQL Injection

Feedback visual de sucesso ou erro com Bootstrap Alerts

Layout responsivo com Bootstrap

🛠️ Tecnologias Utilizadas

HTML5

CSS3

Bootstrap

PHP

MySQL

📂 Estrutura Básica do Projeto
/css
  └── bootstrap.min.css
/js
  └── bootstrap.bundle.min.js
conexao.php
index.php
cadastro.php

🧠 Lógica do Cadastro

Verificação do método de envio (POST)

Captura dos dados do formulário

Sanitização com mysqli_real_escape_string

Inserção na tabela pessoas

Retorno visual ao usuário conforme o resultado da operação

🗄️ Estrutura da Tabela no Banco de Dados (Exemplo)

CREATE TABLE pessoas (

    id INT AUTO_INCREMENT PRIMARY KEY,
    
    nome VARCHAR(100) NOT NULL,
    
    endereco VARCHAR(150),
    
    telefone VARCHAR(20),
    
    email VARCHAR(100),
    
    data_nascimento DATE
);

▶️ Como Executar o Projeto Localmente

Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git](https://github.com/FelipeDevCunha/projetoEmpresa_versao1)

Coloque os arquivos em um servidor local (XAMPP, WAMP ou Laragon)

Crie o banco de dados e a tabela pessoas

Configure o arquivo conexao.php com suas credenciais:

$conn = mysqli_connect("localhost", "usuario", "senha", "nome_do_banco");

Acesse o projeto pelo navegador

📌 Status do Projeto

✔ Versão inicial funcional
🚧 Em desenvolvimento

Próximos passos planejados:

Implementação completa de CRUD (Read, Update, Delete)

Uso de Prepared Statements

Validações avançadas de formulário

Melhor organização do código (MVC simples)

Melhorias de segurança

🤝 Contribuições e Feedback

Sugestões de melhoria são bem-vindas!

Sinta-se à vontade para abrir issues ou enviar feedback.

👨‍💻 Autor

Antonio Felipe Cunha Mathias Chagas (AvançaTech) 

Estudante de back-end em PHP
Projeto desenvolvido para fins educacionais e práticos.
