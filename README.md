# Themes for The Best Django CMS, Mezzanine

## Versiones
```
Mezzanine==4.2.2
Django==1.10.6
Python==2.7
```

## Themes
- default_theme (Default theme for mezzanine)
- base_themes (Base from future themes)
- lightning (Simple and nice theme, blog type, under construction...)

## Use theme
To use each theme it must first be added in the applications installed in the configuration, and you must copy the static folder that the theme brings to the root of the project.

## Installation
```
# pip install -r requirements.txt

$ python manage.py migrate

$ python manage.py createsuperuser

$ python manage.py migrate

$ python manage.py runserver
```
