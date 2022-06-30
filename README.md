<html>
 <body>
<title>
CONFIGURA-O-DJANGO 
 </title>
<br />
 <body>
Configuração inicial para ambiente Django<br />

# Passos <br />
Criar Pasta para o novo Projeto <br />
No Terminal Fedora <br />
 cd documentos <br />
 mkdir Dev <br />
 cd Dev <br />
 mkdir (nome do projeto) <br />
 cd (nome do projeto) <br />
 python -m venv venv <br />
 code . <br />
 
# No terminal VsCode <br />
source venv/bin/activate <br />
pip install django <br />
django-admin startproject <br />

# Banco de Dados <br />
python manage.py migrate <br />
python manage.py runserver <br />
 </body>
</html>
