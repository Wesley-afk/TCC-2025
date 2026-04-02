Readme do projeto StoryBox📦

O StoryBox foi desenvolvido como Trabalho de Conclusão de Curso (TCC), no período de março de 2025 a junho de 2025, com foco em resolver problemas reais de gestão de insumos enfrentados por pequenos negócios, visando a realidade de uma hamburgueria.

A proposta é oferecer uma solução simples, funcional e acessível para melhorar a organização e eficiência operacional.

 📌 Funcionalidades

O sistema oferece:

- Controle de estoque de insumos
- Notificação quando insumos atingem níveis abaixo do ideal
- Feedback visual quando a data de vencimento está próxima
- Gráficos para visualização da saída (evasão) de insumos
- Gerenciamento de **cardápio** e relacionamento de insumos aos itens
- Controle de **nível de usuário** (permissões de acesso)
- Cadastro e gerenciamento de **funcionários**

---

🛠 Tecnologias Utilizadas
Front-end: React.js
Back-end: Node.js
Banco de Dados: MySQL
Servidor Local: XAMPP

📋 Pré-requisitos
Antes de inicializar o projeto, certifique-se que você tem instalado ou instale as seguintes ferramentas:

Node.js
npm
Git
XAMPP
MySQL Workbench

Instalação e Execução

Siga o passo a passo minuciosamente:

1. Clonar o projeto

Abra o terminal na pasta desejada:

git clone <COLE_A_URL_DO_REPOSITÓRIO>
cd TCC_2025

2. Instalar dependências
   
npm install

3. Configurar o banco de dados
   
Abra o XAMPP
Inicie o serviço MySQL
Abra o MySQL Workbench
Vá em File > Open SQL Script
Selecione o arquivo:
Story_tcc02.sql
Execute o script completo selecione o ícone de raio ===>⚡dentro do MySql Workbench

Esse script irá:

Criar o banco de dados
Criar todas as tabelas
Popular o banco com informações para visualizar o projeto

⚠️ Atenção
Não pule essa etapa
O sistema depende do banco para funcionar
Se ocorrer erro:
Verifique se o MySQL está rodando
Apague o banco existente (se houver) e execute novamente

4. Executar o Back-end

No VSCode:

Clique com o botão direito na pasta back
Selecione "Abrir no terminal integrado"

Execute:

node BackEnd.js

5. Executar o Front-end

No terminal do projeto, execute:

npm start

Caso não funcione, acesse a pasta front e execute:

cd front
npm install
npm start

🔐 Acesso ao Sistema

Utilize as credenciais padrão:

Email: ADM@gmail.com
Senha: 123321
