+++
publishDate = "2024-02-27T08:42:21+01:00"
draft = false
title = "Ledger j'ai achete un ledgera 80e"
categories = [ "Crypto", "Informatique" ]
tags = [ "Crypto", "Informatique" ]
+++

# Ledger j'ai achete un ledgera 80e

## Achat

### Pourquoi

- Stockage de crypto peur de les laisser sur un exchange ou sur un wallet que j'aurais oublie plus tard
- Securisation du serveur domestique au vu de l'ouvrir sur l'exterieur

### Difference entre ledger s et ledger x

La premiere difference marquante entre la version s et x du ledger et son **prix** du simple au quasi-double.

Il peut contenir beaucoup moins d'applications, mais pour faire les 1er tests le s allait me suffir.

Pour voir toutes les differences, voici le lien [Ledger wallets comparaison](https://shop.ledger.com/pages/hardware-wallets-comparison)

## Utilisation

### Init

Le packaging du produit est tres propre. La procedure d'initialisation est tres bien explique et je pourrais demander de la faire sans aucun probleme a ma mere,

Le seul element a eclaircir pour elle, serait d'installer les applications sur la cle ainsi que le fait que chaque application represente un compte pour une crypto particuliere.

### crypto

Pour transferer de la crypto sur le ledger, il suffit d'installer l'appli correspondante a la crypto plus de 10 000 sur le ledger a l'heure actuelle. Dans l'application ledger live, il faut ajouter un nouveau compte depuis le ledger et transferer le fond vers l'adresse du compte. Voici les miennes pour exemples 

Bitcoin : bc1qw47dtvzkptesu5e8v9ts4w8pu87lfnhlhtexyh

Ethereum : 0x1EA6ebb6593DbcC2Bd8466D86CA899766a34609B

Posibilite de stacking a l'heure actuel. Cela va surement beaucoup changer dans l'avenir

- Near 9,65% APY
- Tezos 23,53% APY
- Solana 7,33% APY
- Cosmos 16,09% APY
- Ethereum 3,67% APY

### webauthn

Installation de l'application Fido U2F sur le ledger. Connexion au [site d'exemple de webauthn](https://webauthn.io/). Brancher la cle sur l'appareil qui a servi a la navigation vers ce site. Et valider l'authentification sur l'application Fido U2F du ledger

Il est actuellement dommage qu'il n'y ait pas plus de site qui utilise cette facon de s'authentifier.

### Connection ssh et github

Cette partie la de l'article est un peu plus technique. Elle est donc a la fin.

Le tutoriel du blog officiel marche bien je vous le mets ici en lien [Tutoriel du blog officiel](https://www.ledger.com/blog/ssh/)

Il y avait une partie 
> To use this key with your usual SSH Agent and Git, etc

qui n'etait pas assez claire pour moi et qui ma donc fait perdre un peu de temps 
> echo "<ssh://username@hostname|nist256p1>" > "$HOME/.ssh/nanox-keys.conf.pub"

Doit etre remplacer par 
```console
$ echo "ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBCSu3oGKedvLzJpzQr0kGCr7eIyXy67zszMcQCnDUmeAzqlZt9skK0vM/HDquta8vNH77Y9gfjaEWozzfpYCSe0= <ssh://username@hostname|nist256p1>"  > "$HOME/.ssh/nanox-keys.conf.pub"
```

# Tracker

Je suis de retour apres une semaine d'utilisation pour un petit update, c'est quand meme dommage que sur l'application android [Ledger Live](https://play.google.com/store/apps/details?id=com.ledger.live&hl=fr&gl=US&pli=1), il y a d'apres l'application de detection de tracker [Exodus](https://exodus-privacy.eu.org/fr/) 6 pister dont [Facebook](https://facebook.com/), [Google analytics](https://analytics.google.com/), [Goodle tag manager](https://tagmanager.google.com/).

Sinon mis a part ca ca marche toujours tres bien malgre de nombreuses bidouilles en tout genre.

# Conclusion

Je ne regrette pour le moment pas mon achat. Est-ce que je vais assez m'en servir pour l'investissement que ca repressente, c'est une autre question ?
