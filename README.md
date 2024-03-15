# Nome do projeto

Pequeno resumo do projeto.

## ✔️ Tecnologias usadas
- Python
- Django
- Django Rest Framework
- PostgreSQL
- Simple JWT
- Swagger/Redoc
- Vercel

## 📁 Acesso ao deploy

[![Deploy with Vercel](https://vercel.com/button)](https://www.google.com.br/?hl=pt-BR)

## 🔨 Funcionalidades

- **Teste**: Crie, atualize, leia e delete.

## 📌 Uso

Nome do projeto segue os princípios REST para comunicação. Os seguintes endpoints estão disponíveis:

### /users/
- Gerenciar usuários e realizar operações CRUD.

## 🔐 Autenticação

A autenticação é realizada através de JWT. Utilize a rota `/token/` para obter um token de acesso, enviando as credenciais do usuário. Utilize este token nas requisições subsequentes para autenticar.

## 🛠️ Abrindo e rodando o projeto

Para configurar a Requisitions API em seu ambiente, siga estas etapas:

1. Clone o repositório do projeto para sua máquina local.
2. Configure o ambiente virtual para Python e ative-o.
3. Instale as dependências do projeto
```bash
pip install -r requirements.txt
```
4. Configure as variáveis de ambiente necessárias para a conexão com o banco de dados e outras configurações de sistema.
5. Execute as migrações do banco de dados
```bash
python manage.py migrate
```
6. Crie um super usuário para ter acesso a `/admin/`
```bash
python manage.py createsuperuser
```
7. Inicie o servidor de desenvolvimento
```bash
python manage.py runserver
```
