+++
publishDate = "2019-03-20T18:04:04+01:00"
draft = false
title = "Domoticz et telegram"
categories = [ "domotique", "domoticz", "telegram", "bot", "clé d'api", "chat id" ]
+++
# Notification d'un bot telegram par domoticz
## Installation
[Telegram](https://fr.wikipedia.org/wiki/Telegram_(application)) est un logiciel de messagerie instanée à l'instar de What'sApp.

Installation de telegram sur le telephone.

Connection avec son numéro de téléphone.

Discussion avec BotFather.

"/start"

"/newbot"

"botname" like Pidomotticz

"username" like DomPiBot

Réponse du bot avec un token.
Pour le copier coller plus facilement il existe une App télégram web [https://web.telegram.org](https://web.telegram.org)

Créé dans l'application telegram un nouveau canal.

Ajouter comme administrateur du canal le nom de notre bot.

"ecrires quelques messages dans le canal"

Aller sur l'url [https://api.telegram.org/bot784324329:EETXXXGuuuL/getUppublishDates]
Penser à changer le token avec le votre.

Vous allez retrouver votre Chat ID. Il peut être négatif.

Tester votre bot avec l'url suivante [https://api.telegram.org](https://api.telegram.org)
Pour moi avec l'url suivante [https://api.telegram.org/bot784324329:EETRNJU3jQEGWQdjNv3llb4bnDSDREGuuuL/sendMessage?chat_id=1234567&text=Hello]

Les liens utils :
[doc officiel de domoticz](https://www.domoticz.com/wiki/Telegram_Bot) pas mal mais quelques parties obsolètes ou pas très claires.

Dans domoticz vous pouvez aller dans Réglages=>Paramètres=>Notification.

En bas à droite vous avez 2 champs télégram avec la clé de l'api et le chat id.

## Utilisation
Frigo ou congélateur trop chaud

La box ne répond plus au ping

...
