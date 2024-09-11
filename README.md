
# CRUD Básico em Laravel

![Laravel](https://img.shields.io/badge/Laravel-v10.x-red) 
![Bootstrap](https://img.shields.io/badge/Bootstrap-v4-blue) 
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-v12-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 📋 Introdução

Este projeto é um exemplo de CRUD básico desenvolvido em Laravel, utilizando Bootstrap 4 para estilização e Ajax para operações assíncronas no padrão MVC. A aplicação conecta-se a um banco de dados PostgreSQL com uma tabela de produtos.

## 🛠 Requisitos

- PHP >= 8.1
- Composer
- Laravel 10.x
- PostgreSQL >= 12
- Node.js com NPM
- Git

## 🚀 Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/siqueira1989/php.git
   cd seuprojeto
   ```

2. Instale as dependências do PHP:
   ```bash
   composer install
   ```

3. Instale as dependências do Node.js:
   ```bash
   npm install
   ```

4. Configure o arquivo `.env`:
   - Copie o arquivo de exemplo:
     ```bash
     cp .env.example .env
     ```
   - Atualize as credenciais do banco de dados no `.env`:
     ```plaintext
     DB_CONNECTION=pgsql
     DB_HOST=127.0.0.1
     DB_PORT=5432
     DB_DATABASE=teste
     DB_USERNAME=seu_usuario
     DB_PASSWORD=sua_senha
     ```

5. Gere a chave da aplicação:
   ```bash
   php artisan key:generate
   ```

6. Execute as migrações do banco de dados:
   ```bash
   php artisan migrate
   ```

7. Inicie o servidor local:
   ```bash
   php artisan serve
   ```

8. Acesse a aplicação em seu navegador:
   ```
   http://localhost:8000
   ```

## 📝 Uso

- **Listar Produtos:** Acesse a página inicial para ver a lista de produtos cadastrados.
- **Adicionar Produto:** Utilize o formulário para adicionar um novo produto via Ajax.
- **Editar Produto:** Edite um produto existente clicando no botão "Editar".
- **Excluir Produto:** Exclua um produto clicando no botão "Excluir".

## 🗂 Estrutura do Banco de Dados

Banco de dados: `teste`

Tabela: `produtos`

| Coluna     | Tipo         | Descrição                |
|------------|--------------|--------------------------|
| id         | Integer      | Chave primária           |
| nome       | String       | Nome do produto          |
| descricao  | Text         | Descrição do produto     |
| preco      | Decimal(10,2)| Preço do produto         |
| created_at | Timestamp    | Data de criação          |
| updated_at | Timestamp    | Data de atualização      |

## 🛠 Tecnologias

- **Laravel** - Framework PHP para construção de aplicações web.
- **Bootstrap 4** - Framework CSS para estilização responsiva.
- **Ajax** - Para operações assíncronas entre frontend e backend.
- **PostgreSQL** - Sistema de gerenciamento de banco de dados relacional.

## 📚 Documentação

- [Documentação do Laravel](https://laravel.com/docs/10.x)
- [Documentação do PostgreSQL](https://www.postgresql.org/docs/)
- [Documentação do Bootstrap 4](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- [Documentação do JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

## 📞 Contato

Para mais informações, entre em contato:

- **Email:** seuemail@example.com
- **GitHub:** [Seu Perfil](https://github.com/seuusuario)

---

© 2024 Seu Nome - Este projeto está licenciado sob a licença MIT.
# laravel
