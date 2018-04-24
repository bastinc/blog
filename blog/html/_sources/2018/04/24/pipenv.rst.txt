Pipenv
======



.. author:: default
.. categories:: none
.. tags:: none
.. comments::



Installer pipenv

::

    sudo pip3 install pipenv

    
1) Créer un environnement virtuel pour le projet en spécifiant la version de python(Pour peu que la version soit installée sur le système)

::

    pipenv --three

Un fichier "Pipfile" est généré ainsi qu'un fichier Pipfile.lock

2) Ouvrir l'environnement virtuel dans un shell

::

    pipenv shell


3a) Installer à partir d'un fichier Pipfile existant

::

    pipenv install

3b) Installer une nouvelle librairie

::

    pipenv install [Library_name]



L'environnement virtuel créé se trouve dans le dossier ~/.local/share/virtualenvs
