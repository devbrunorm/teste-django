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