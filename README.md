# Projeto Controle de Funcionário - Django

Nesse projeto foi usado o Framework Django no Pycharm e produzido como parte do artigo sobre Desenvolvimento Web com Django da Python Academy. Para criar esse projeto, foi seguido um roteiro de passo a passo para facilitar a produção do projeto da seguinte forma: 
* Criar my-project no Heroku. 
* Instalar heroki-cli.
* Fazer login e associar o projeto local com o remoto.
* Preparando as dependências para instalar no Heroku.
* Instalando o Gunicorn para servir a aplicação no Heroku e django-on-heroku.
* Determinando a versão do python executada no Heroku.
* Configurando o arquivo Procfile + Dica extra.
* Fazendo o Deploy.
* Executando o migrate e criar um superuser.
* Desacoplando variáveis específicas de ambiente com o python-decouple.
[Acesse aqui](https://pythonacademy.com.br/blog/desenvolvimento-web-com-python-e-django-introducao) 
e saiba mais!

## Instalação

Primeiro, recomenda-se a criação de um ambiente virtual. 

_Quer saber mais ambientes virtuais? Então [acesse o link para nosso post 
sobre ambientes virtuais no Python](https://pythonacademy.com.br/blog/python-e-virtualenv-como-programar-em-ambientes-virtuais)!_

Com seu ambiente virtual configurado, instale as dependências do projeto com:

```bash
pip install -r requirements.txt
```

Para criar as _Migrations_:

```bash
python manage.py makemigrations
```

Para efetivar as _Migrations_ no banco de dados:

```bash
python manage.py migrate
```

## Execução

Para executar o servidor de testes do Django, execute:

```bash
python manage.py runserver
```

## Fique por dentro

Se gostou do conteúdo, siga a Python Academy no nosso blog e redes sociais!

- [Site](https://pythonacademy.com.br)
- [Facebook](https://facebook.com.br/pythonacademy/)
- [Blog](https://pythonacademy.com.br/blog/)

E até a próxima!
