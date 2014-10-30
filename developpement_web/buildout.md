## Python Buildout

La formation Python Buildout présente les techniques de déploiement automatisé et répétable de projets logiciels basés sur l'outil "zc.buildout".

## Objectif
   * Apprendre à automatiser le déploiement d'un environnement pour des projets web complexes (CMS, LAMP, Web Framework) avec zc.buildout

### Pré-requis
   * Connaissance de Python
   * La connaissance d'un environnement serveur web serait un plus (Zope, Lamp, Plone...)

### Public
  * Développeurs
  * Administrateurs Systèmes

### Durée
* 1 jour

## Prix
* 500 €

### Programme
1. Présentation de l'outil Buildout
  * Outil prédictible : Gestion des conflits contrairement à easy_install ou pip
  * Outil reproductible : 'pinner' les versions, reproduire le comportement sous plusieurs environnements
  * Outil extensible : Extensions des fichiers de config, extensions tierces (buildout.dumpickled_version, mr.developper, omelette
  * Outil « project centric » : Déploiement sous différents environnements, développement, préprod, production
2. Notions fondamentales
  * Sys.path (site-packages)
  * Namespaces et packages
  * Distribution sous forme d'egg
  * Setup.py
  * Easy_install, pip, virtual_env
3. Les sections d'un Buildout
  * Variables globales
  * Parts
  * Eggs
  * Developp
  * Références
  * Recipe
4. Gérer un projet
  * Étendre un buildout
  * Base.cfg
  * Dev.cfg
  * Prod.cfg
5. Tester un projet
  * Ajout d'une part tests
  * Couplage du buildout à un environnement de tests d'intégration continue (jenkins)
  * Mr.developper, dump_picked_versions, omelette (avec des extensions tierces)
6. Couplage de buildout avec paste.script
  * ZopeSkel, écrire son propre template pour les eggs, pour un projet (génération d'eggs, de buildout.cfg
