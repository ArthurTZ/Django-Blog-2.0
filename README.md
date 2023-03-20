# Django-Blog

### Pré-requisitos
Antes de começar, certifique-se de que você tenha os seguintes requisitos instalados em seu sistema:
- Python (versão 3 ou superior)
- pip (gerenciador de pacotes do Python)
- confira o arquivo (requirements.txt)

## Segue-se passo a passo para se criar um blog simples com validação de usuario
- Nesse projeto utilizamos templates prontos de bootstrap5 para facilitar o processo de criação e com o foco principal no back-end
- Links utilizados: https://getbootstrap.com/,
- niceadmin do bootstrap5 facilita muito o front -(https://bootstrapmade.com/nice-admin-bootstrap-admin-html-template/)
- Documentação oficial: https://docs.djangoproject.com/en/4.1/ 	

- Primeiro passo: Instalação e configuração do projeto
- instalações: esta no requirements (requirements.txt)

### Inicio: primeiro comando para iniciar:
	django-admin startproject <nome do projeto>
	seguindo a documentação do django, é necessario que teste antes usando:
	Python manage.py runserver (comando para iniciar o servidor de testes);
###  em seguida vamos iniciar a criação do app (em um projeto pode-se ter varios apps):
	 python manage.py startapp <nome do app>
- logo em seguida é obrigatorio colocar o nome do app dentro dos INSTALLED_APPS em settings.py
### INSTALLED_APPS = [
	'django.contrib.admin',
	'django.contrib.auth',
	'django.contrib.contenttypes',
	'django.contrib.sessions',
	'django.contrib.messages',
	'django.contrib.staticfiles',
	'blog.apps.BlogConfig', <- (nome do app)
	'django_project', <- (nome do projeto)
	'users', <- (nome do app)
	'crispy_forms', <- (nome das instalações que é obrigatorio por aqui)
	'crispy_bootstrap5',<- (nome das instalações que é obrigatorio por aqui )
]
### Segundo-passo : Configurações dos Apps:
- agora começa o inicio dos Apps
### Crie um novo aplicativo Django usando o comando:
	python manage.py startapp
### em seguida execute os seguintes passos:
	1° - Crie um novo modelo para o seu aplicativo no arquivo models.py.
	2° - Defina as rotas do seu app no arquivo urls.py.
	3° - Adicione seu aplicativo à lista de aplicativos instalados no arquivo settings.py.
	
## Feito todos os passos acima, ja é o suficiente para começar um novo app de sua preferencia!	
	
