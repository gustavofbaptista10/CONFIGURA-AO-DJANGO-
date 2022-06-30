# CONFIGURA-O-DJANGO-
Configuração inicial para ambiente Django

# Passos
Criar Pasta para o novo Projeto
No Terminal Fedora
 cd documentos
 mkdir Dev
 cd Dev
 mkdir (nome do projeto)
 cd (nome do projeto)
 python -m venv venv
 code .
 
# No terminal VsCode
source venv/bin/activate
pip install django
django-admin startproject 

# Banco de Dados
python manage.py migrate
python manage.py runserver
