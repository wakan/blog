+++
date = "2016-10-24T19:42:21+02:00"
draft = ture
title = "Attaque ddos"
categories = [ "Hacking", "Informatique" ]
+++

# Dyn : attaque DDoS

Les attaques ddos sont de plus en plus répendus.
On peut voir d'en l'actualité en ce moment 
[News attaque ddos](http://www.nextinpact.com/news/101871-dyn-on-fait-point-sur-attaque-ddos-qui-a-impactee-nombreux-sites.htm).
Il serait temps, à notre époque avec les moyens actuelles, de trouver des solutions pour pouvoir les éradiquer.

## Vecteur de réflextion 1 : Sécurisation des postes zombies

Mettre en place des controles au niveau du système d'exploitation. Afin d'éviter ce genre d'attaque.
Je ne suis pas fan de cette technique car j'aime avoir la maitrise complète de mon matériel.

Ce vecteur est un vecteur difficile à exploiter.
Au mieux, on pourrait avertir l'utlisateur moyen afin qu'il se fasse aider ou qu'il fasse plus attention.

##Vecteur de réflexion 2 : Controle du trafic par les FAI.

On a vu dans le chapitre précédent qu'il était compliquer à demander à tous les utilisateurs de garder leurs systèmes sécurisés.
En même temps ce n'est pas leur boulot pourquoi ils devraient s'embeter avec cela ?

Sans rentrer dans l'extrème comme [Hadopi](https://www.hadopi.fr), 
les FAI pourraient mettre en place des sécurités pour couper notre trafic réseau en cas de surconsomation sur une courte période.

Lors d'un pic de trafic, le FAI pourrait demander une confirmation à l'utilisateur par sms pour confirmer que le trafic est normal.
En cas de non réponse, il pourrait couper le trafic de l'utilisateur en question.

Il pourrait aussi mettre en place du [machine learning](https://fr.wikipedia.org/wiki/Apprentissage_automatique) 
afin de dectecter des utilisateurs à risque ou dont le profil est à surveiller en priorité.

## Analogie de pc zombie avec des dealers

Les pc zombies est un buisiness fructueux pour un petit hacker sans envergure.
En effet, il touche environ 200€ par pc infecté par un rootkit. 
On pourrait donc comparer ces personnes à des dealers.
Plus haut dans la hiérarchie, il y a les personnes qui controle les rootkit. 
Ils s'en servent le plus souvent pour élimer la concurrence en rendant leurs services indisponnibles.
On pourrait donc comparer ce genre de personne aux chefs de cartels.

##Le mot de la fin

Faite vos mise à jour.
Si il y en a c'est pas pour rien.
Cela corrige des failles de sécurités exploitées par les petit hacker sans envergure.

