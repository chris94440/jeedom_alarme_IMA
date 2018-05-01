= Aide du plugin "Alarme IMA téléassistance"

== Description
Ce plugin permet d'afficher le statut de votre alarme IMA téléassistance (commercialisée notamment par la MACIF).


== Prérequis
Vous devez tout d'abord activer l'option "Pilotage à distance" de votre alarme.
Ceci peut se faire gratuitement en appelant IMA téléassistance.
Vous obtiendrez alors un login/mot de passe d'accès au site: https://pilotageadistance.imateleassistance.com .


== Création de l'alarme
Une fois le plugin installé:

- cliquez sur Plugins > Sécurité > Alarme IMA
- puis cliquez sur l'icône "+"
- dans la fenêtre qui s'ouvre, choisissez un nom d'équipement, par exemple: "Mon alarme".
- vous arrivez alors à la page de configuration de votre alarme:

[.text-center]
image::doc.png[Configuration]

[NOTE]
===
Le login / mot de passe à configurer ici est celui qui vous permet d'accéder à https://pilotageadistance.imateleassistance.com (voir section Prérequis).
Ces identifiants sont stockés uniquement dans votre jeedom et servent à récupérer le statut de l'alarme. 
===

- enfin, cliquez sur Sauvegarder.

[IMPORTANT]
====
Pensez à

* choisir un objet parent,
* cliquer sur activer,
* cliquer sur visible.

Sans ces 3 conditions, vous ne verrez pas votre alarme sur le dashboard jeedom.
====


== Voir le statut de l'alarme
Cliquez maintenant sur Accueil > Dashboard : un nouveau widget apparaît, qui représente le statut actuel de l'alarme.

[.text-center]
image::widget.png[Widget]

3 statuts sont possibles:

- ON (l'alarme est en marche), 
- OFF (l'alarme est éteinte), 
- PARTIAL (l'alarme est active sur une partie de votre domicile uniquement).


== FAQ
include::faq.asciidoc[]