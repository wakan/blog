+++
date = "2016-10-24T19:42:21+02:00"
draft = false
title = "Attaque ddos"
categories = [ "Hacking", "Informatique" ]
+++

# Dyn : attaque DDoS

Les attaques ddos sont de plus en plus répendues.
On peut voir dans l'actualité en ce moment 
[News attaque ddos](http://www.nextinpact.com/news/101871-dyn-on-fait-point-sur-attaque-ddos-qui-a-impactee-nombreux-sites.htm).
Il serait temps, à notre époque, avec les moyens actuels, de trouver des solutions pour pouvoir les éradiquer.

## Vecteur de réflextion 1 : Sécurisation des pc zombies

Mettre en place des contrôles au niveau du système d'exploitation. Afin d'éviter ce genre d'attaque.
Je ne suis pas fan de cette technique, car j'aime avoir la maîtrise complète de mon matériel.

Ce vecteur est un vecteur difficile à exploiter.
Au mieux, on pourrait avertir l'utilisateur moyen afin qu'il se fasse aider ou qu'il fasse plus attention.

## Vecteur de réflexion 2 : Controle du trafic par les FAI.

On a vu dans le chapitre précédent qu'il était compliqué de demander à tous les utilisateurs de garder leurs systèmes sécurisés.
En même temps, ce n'est pas leur boulot, pourquoi ils devraient s'embêter avec cela ?

Sans rentrer dans l'extrême comme [Hadopi](https://www.hadopi.fr), 
les FAI pourraient mettre en place des sécurités pour couper notre trafic réseau en cas de sur consommation sur une courte période.

Lors d'un pic de trafic, le FAI pourrait demander une confirmation à l'utilisateur par SMS pour confirmer que le trafic est normal.
En cas de non-réponse, il pourrait couper le trafic de l'utilisateur en question.

Il pourrait aussi mettre en place du [machine learning](https://fr.wikipedia.org/wiki/Apprentissage_automatique) 
afin de déctecter des utilisateurs à risque ou dont le profil est à surveiller en priorité.

## Analogie de pc zombies avec des dealers

La fabrication de pc zombies est un business fructueux pour un petit hacker sans envergure. 
En effet, il touche environ 200€ par pc infecté par un rootkit. 
On pourrait donc comparer ces personnes à des dealers. 
Plus haut dans la hiérarchie, il y a les personnes qui contrôlent les rootkits. 
Ils s'en servent le plus souvent pour élimer la concurrence en rendant leurs services indisponnibles. 
On pourrait donc comparer ce genre de personne aux chefs de cartels.

## Le mot de la fin

Faites vos mises à jour.
S'il y en a, ce n'est pas pour rien.
Cela corrige des failles de sécurité exploitées par les petits hackers sans envergure.

