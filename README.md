# Teste do Django (Alura Receitas)

Projeto desenvolvido para fins de aprendizado sobre o framework Django.
Para esse projeto o banco de dados utilizado foi o PostgreSQL.

Criando o venv:

```
python -m venv ./venv
```

Rodando o venv:

```
. .\venv\Scripts\activate.bat //CMD
venv\Scripts\activate.ps1 // PowerShell
```

Rodar o servidor:

```
python manage.py runserver
```

Iniciando o app:

```
python manage.py startapp receitas
```

Incluindo os arquivos estáticos no projeto:

```
python manage.py collectstatic
```

Criando migração:

```
python manage.py makemigrations
```

Rodando migrações:

```
python manage.py migrate
```

# Para execução do sistema, é necessário a criação em um arquivo .env contendo as seguintes informações:

```
DATABASE_NAME="Nome da sua base de dados"
DATABASE_USER="Username da seu banco de dados"
DATABASE_PASSWORD="Senha da seu banco de dados"
DATABASE_HOST="Endereço da sua base dados"
SECRET_KEY="Chave do seu Django"
```

Basta apenas informar os dados solicitados e salvar o arquivos .env no diretório alurareceita/.