# Django_01
Grupos de repositorios para aprender Django

## Git log "Project Django "django_01" created"

### Documents

1) Creación del entorno virtual, activación y creación del archivo requirements.txt.

```bash
python -m venv virtualE
source virtualE/bin/activate
pip install django
pip freeze > requirements.txt
```

### Documents
* #### virtualE
* #### requerements.txt

2) Clonacion del repositorio Django_00 desde Github.

```bash
git clone https://github.com/usuario/Django_01.git
```

### Documents
* #### virtualE
* #### requerements.txt
* #### Django_01

3) Instalación de Django, actualización de requirements.txt y creación del projecto django_01.

```bash
pip install django
pip freeze > requirements.txt
django-admin startproject django_01
python manage.py runserver 
```

### Documents
* #### virtualE
* #### requerements.txt
* #### Django_01
	* ##### django_01 
	* ##### manage.py
	* ##### .git
	* ##### README.md

4) Add, Commit y Push del repositorio local al remoto.

```bash
git add .
git commit -m "Project Django 'django_01' created"
git push orign main
```