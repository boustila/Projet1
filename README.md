### Projet 1
## Architecture de l'application
<p>
  on utilise le MVC car:L'architecture MVC  ou ,Modèle-Vue-Contrôleur, est un modèle formé de 3 composants : l'un chargé de recevoir les requêtes, un autre de traiter les données 
et un troisième de préparer l'affichage.
Si les interfaces entre ces trois composants sont clairement définies, il devient facile d'en modifier un sans toucher aux deux autres.
Le modèle implante les fonctionnalités de l’application,est également responsable de la préservation de l’état d’une application entre deux requêtes HTTP.
    il  est chargé de la gestion des données, notamment des interactions avec la base de données.
La vue est responsable de l’interface, ce qui recouvre essentiellement dans notre cas les fragments HTML.
Le rôle des contrôleurs est gestion des événements et synchronisation et de récupérer les données utilisateurs, de les filtrer et de les contrôler, de déclencher le traitement approprié (via le modèle), et finalement de déléguer la production du document de sortie à la vue(on utilise servler).</p>

## l'architecture de la couche de donnée
<p>
  Le moment est venu de mettre en place notre base de données pour compléter l’architecture de notre application. Tous ce qui suit utilise MySQL.
Nous avons besoin de quelques installations complémentaires:</p>

+ MySQL
+ un outil d’administration et de gestion de nos bases, phpMyAdmin
+ les librairies de connexion Java/MySQL
 
  
  ## maniére de gestion de demande de client
  + le client entrer dans la page d'accueil,il depose son document et choisie le type de conversion et entrer un mail de contact
  + Les composants de cette catégorie reçoivent les requêtes des clients, les traitent et les transmettent aux composants chargés de traiter les données une servlet peut jouer ce rôle et leur retourner une réponse
  + si la conversion est terminer elle envoi un lien de telechergement
  
  ## les technologies choisies pour le dévloppement est 
  <p>
  Les servlets : Les servlets ont de nombreux avantages par rapport aux autres technologies côté serveur. Tout d'abord, étant donné qu'il s'agit d'une technologie Java, les servlets fournissent un moyen d'améliorer les serveurs web sur n'importe quelle plateforme, d'autant plus que les servlets sont indépendantes du serveur web (contrairement aux modules apache ou à l'API Netscape Server). En effet, les servlets s'exécutent dans un moteur de servlet utilisé pour établir le lien entre la servlet et le serveur web. Ainsi le programmeur n'a pas à se soucier de détails techniques 
tels que la connexion au réseau, la mise en forme de la réponse HTTP, ... 
</p>
  
