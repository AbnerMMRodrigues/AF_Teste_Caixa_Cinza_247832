# AF_Teste_Caixa_Cinza_247832

# Introdução

A atividade consiste na aplicação de testes de caixa cinza utilizando o Supabase (banco de dados) e o Postman (ferramenta para testes com requsições).

O intuito da atividade é demonstrar e aplicar o conhecimento adquirido em aula sobre testes de caixa cinza e das ferramentas utilizadas.

# Objetivo da Atividade

## 4.1 Objetivo Geral

Criar um banco de dados no Supabase e realizar testes com o mesmo através do Postman.

## 4.2 Objetivos Técnicos

- criar e configurar um banco de dados no Supabase;
- criar e configurar um workspace, collection e environment no Postman;
- realizar testes com o banco de dados criados através do workspace criado no Postman;

# Configuração do Supabase

O processo de criação do banco no Supabase foi feito da seguinte maneira:

Criar Conta no Supabase -> Criar uma Organização nova -> Criar um Projeto

Após criar o projeto, o banco foi criado juntamente a ele.

Com o projeto criado, o primeiro passo foi navegar até o sub-menu de autenticação na barra lateral, depois disso, a opção "Sign-in / Providers". Lá, garantimos que a opção "email" está "enabled" na parte de Auth Providers.

Depois disso, ainda no sub-menu de autenticação, fomos para a opção "Users" e criamos um novo usuário, com e-mail e senha, e então anotamos essas credenciais.

Com isso, voltamos ao menu principal do projeto, e coletamos a API_Key e a Base_URL do projeto.

### PROJETO CRIADO/PAINEL

!["Projeto Criado"](prints/Supabase_Painel.png)

### AUTENTICAÇÃO HABILITADA

!["Autenticação"](prints/Supabase_Autenticação_Habilitada.png)

### USUÁRIO CRIADO

!["Usuário"](prints/Supabase_Usuario_Criado.png)

### CREDENCIAIS DA API

!["Usuário"](prints/Supabase_Credenciais.png)

# Configuração do Postman

O processo de criação do banco no Supabase foi feito da seguinte maneira:

Baixar o CLI do Postman Desktop -> Criar uma Conta no Postman -> Criar um novo Workspace

Com o novo workspace criado, o primeiro passo é criar um Environment. Foi clicado no "+" ao lado da barra de pesquisa no topo da barra lateral esquerda, e selecionada a opção "Environment" para ser criado.

Com ele criado, as seguintes variaveis foram inseridas no mesmo:

**base_url:** base_url do projeto no supabase
**api_key:** api_key do usuario no supabase
**email:** email do usuario cadastrado no supabase
**senha:** senha do usuário cadastrado no supabase
**acess_token:** mesmo dado da API_Keuy

Após a configuração do Environment, no painel inicial do POSTMAN, selecione o Environment criado no topo superior direito para ele ser usado e o Postman conseguir ter acesso ao banco do Supabase.

### Workspace

!["Workspace"](prints/Postman_Workspace.png)

### Environment e Variaveis

!["Autenticação"](prints/Postman_Environment_e_Variaveis.png)

# Configuração das Requisições

# Execução dos Testes

# Registro dos Testes

# Resultados Obtidos

# Conclusão
