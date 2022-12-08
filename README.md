Comandos para preparar o ambiente:

1 - Criar ambiente virtual:
    python -m venv venv

2 - Ativar ambiente virtual:
    venv/Scripts/activate

3 - Instalar bibliotecas do projeto:
    pip install -r requirements.txt

4 - atualizar pip:
    python -m pip install --upgrade pip


Comandos para rodar o projeto:

1 - Caso queira rodar o projeto:
    python manage.py runserver

2 - Caso queira criar as tabelas:
    python manage.py migrate

3 - Para criar um superusuario:
    python manage.py createsuperuser (user: admin - senha: 1234)
    Para acessar o painel de admin do django:
        http://127.0.0.1:8000/admin

# Integração com bootstrap
1 - Criar uma pasta "static" na raiz do projeto:
2 - Baixar o css do bootstrap https://getbootstrap.com/docs/4.1/getting-started/download/  e colar seu conteúdo 
na parte static/bootstrap