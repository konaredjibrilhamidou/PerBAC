# PerBAC
Pervasive Based Access Control Model

 Introduction 
------------
Cette bibiotheque permet une implementation pratique du modele d'acces **PerBAC**.

Nous choisissons de construire notre modèle basé principalement sur ABAC comme un modèle global AC standard [11] qui, d'une part utilise le concept d'attributs très avantageux dans les environnements décentralisés IoT, et d'autre part inclut plusieurs concepts abstraits et autres modèles AC génériques tels que RBAC. 

Pour implémenter le modèle PerBAC, nous devons définir les exigences d'un environnement IoT standard en matière de contrôle d'accès. Il est clair qu'un environnement IoT pourrait avoir des exigences différentes changeant d'un contexte à l'autre. Cependant, sans certaines exigences globales qui entourent les situations IoT standard, nous ne pouvons pas définir un modèle CA qui les traitera avec efficacité.

Pour plus de details :

Installation 
-----------
Installer java-JDK :

`sudo apt-get install openjdk-7-jdk`

Cloner PerBAC :

`git clone https://github.com/esalim/PerBAC.git`

Telecharger la bibiotheque JSON :

`https://jar-download.com/artifacts/org.json`

Importer la bibliotheque:

`javac -cp json-20180813.jar yourfilename.java `.


Exemple
-------

