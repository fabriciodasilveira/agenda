
Iniciar o projeto Django

```
python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
```

Usuário ADM para teste

```
fsilveira
```

Migrando a base de dados do Django

```
python manage.py makemigrations
python manage.py migrate
```

Criando um super usuario no Django

```
python3 manage.py createsuperuser
python3 manage.py changepassword USERNAME
```


Criando Model no Django

```
Dentro do aplicativo contact criado existe um arquivo models.py, crie os models dentro desse arquivo
```

Registrar o Model dentro do ADMIN do Django

```
Arquivo admin dentro do app do projeto
Para registrar usamos o Decorator @admin.regiter("Passando o Model")
```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
```

