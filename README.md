# Teste-Pratico-Sistema-de-cadastro-de-usuarios


# Sistema de Cadastro de Usuários

Este projeto é um sistema de cadastro de usuários, desenvolvido utilizando PHP para o backend, Bootstrap para o frontend e MySQL para o banco de dados. O projeto foi configurado para ser executado no XAMPP, utilizando o phpMyAdmin para gerenciar o banco de dados.

## Estrutura do Projeto

### Arquivos e Funções

- **index.php**: Tela principal que permite o cadastro e pesquisa de usuários.
- **pesquisar.php**: Página para pesquisa de usuários.
- **cadastro.html**: Página dedicada ao cadastro de novos usuários, com campos para nome, data de nascimento e e-mail.
- **cadastro_edit.php**: Responsável pela edição de usuários.
- **conexao.php**: Script para conexão com o banco de dados.
- **cadastro_script.php**: Script para processar o cadastro de usuários.
- **edit_script.php**: Script para processar a edição de usuários.
- **excluir_script.php**: Script para excluir usuários do banco de dados.

### Estrutura do Banco de Dados

O banco de dados contém a seguinte tabela:

- **usuarios**: Armazena os dados dos usuários do sistema.

### Dependências

- **XAMPP**: Para execução do servidor local.
- **phpMyAdmin**: Para gerenciamento do banco de dados MySQL.
- **Bootstrap**: Para estilização do frontend.

## Configuração e Execução

1. **Instalar e Configurar o XAMPP**:
   - Baixe e instale o XAMPP.
   - Inicie o servidor Apache e MySQL através do painel de controle do XAMPP.

2. **Configurar o Banco de Dados**:
   - Acesse o phpMyAdmin através do navegador: `http://localhost/phpmyadmin`.
   - Crie um banco de dados chamado `registros`.
   - Importe as tabelas `pessoa` e `usuario` no phpMyAdmin.

3. **Configurar o Projeto**:
   - Coloque todos os arquivos do projeto na pasta `C:\xampp\htdocs\Teste Pratico\Teste-Pratico-Sistema-de-cadastro-de-usuarios`.

4. **Acessar as Páginas**:
   - Como os botões de navegação não estão funcionais, abra as páginas diretamente pelo URL:
     - Para cadastro de usuários: `http://localhost/Teste%20Pratico/Teste-Pratico-Sistema-de-cadastro-de-usuarios/cadastro.html`
     - Para pesquisar usuários: `http://localhost/Teste%20Pratico/Teste-Pratico-Sistema-de-cadastro-de-usuarios/pesquisar.php`

## Problemas Conhecidos

- **Conexão com o Banco de Dados**: Problemas ao encontrar as páginas e conectar ao banco de dados.
- **Segurança**: A segurança nos campos de e-mail e senha não está totalmente implementada.
- **Formatação**: Alguns problemas de formatação no frontend.

## Recomendação

Para abrir o projeto e testar localmente, recomendo a seguinte estrutura de diretórios:![image](https://github.com/user-attachments/assets/8f9546b4-ea6b-437c-8281-d5e76e1d57d3) ![image](https://github.com/user-attachments/assets/206c559d-6e8f-43d5-8e28-eba76184be46)




