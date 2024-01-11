# Notes de reunion

## **Point Init et config 19 sept**

Lionel  [<l@blueandblue.fr>](mailto:%3cl@blueandblue.fr%3e),

Yassine [<y@blueandblue.fr>](mailto:%3cy@blueandblue.fr%3e),

Marie [<m@blueandblue.fr>](mailto:%3cm@blueandblue.fr%3e)

John DOE

CMS : au début WebEdition sans e-commerce en Suisse

ERP ok Microsoft Business Central

Christelle SEA SEO

**Yassine** (PrestaShop contributeur & créa graphique)

septembre octobre de début de l'hiver

1000K CA site web

## **Réunion du 16/09 => 22/09**

- **Serge**
- un **PPT propal** "comme CodeIn"
- un **PDF** contrat + CGV
- un **GDrive / Gdoc partagé** de log et suivi des Reunions (historisé, collaboratif) + email si demande

TMA & projets (Chiffrage, Dev, Migration, gestion de projet, TMA, .... ) :

- Sylvanian Families refonte de Drupal vers PrestaShop 1.7
- Magimix & module Sofinco paiement/financement em pleine migration 1.6 to 1.7
- La malle à thé (ajout d'un site) sur un multi site 1.7 avec refonte connecteur ETL/Entrepôt
- Nos bons plats chez vous Mise en prod de la refonte en 1.7
- Reitzel et Jardin d'Orante 1.7 rattrapage d'une TMA qui dérappe
- Rousseau 1.6 (robinetterie, etc) multisite
- Lemon curve (2014)
1. Echanges / reprise ancien prestataire ? Besoin ou possible ??
2. Mise en place et accès de votre Redmine
3. Mise en place de réunion régulière si activité.
4. Atelier metier
    1. taches régulières / taches saisonnière (inventaire, période de rush/freeze IT)
    2. evolution à venir stratégie et enjeux
5. Ancien prestataire ou Blue&Blue : versions Wordpress / Prestashop ...
    1. accès au back offices actuel
    2. modules utilisés
    3. mode d'interaction (passage de l'un à l'autre) : module , séparés, incorporés, api
    4. ...
6. CodeIn + Macaron : Dockerisation de Prestashop + Wordpress
    1. archi & infra utilisé / cible
7. Blue&Blue + Macaron : liste des taches déjà identifiées
    1. bug & pb connus
    2. evolution CT / LT
8. Autres briques/element
    1. CDN, cache redis, memcache, sauveguardes
    2. intervention sur les commandes, exports de données, imports de données
    3. renouvellement de contrat : domaine, modules de paiements, logiciels tiers
    4. modes de paiement
    5. liste des modules utilisés / non utilisés
    6. liste des utilisateurs actifs et droits
    7. mot de passe du compte admin / user et roles à jours ?
    8. liste des flux / connexions à d'autre services

## **Call le 25** **aout**

- chiffrage toujours avant de commencer

à 25% prêt

pour la confiance on est presque en régie grace à ça

client congés en aout jusqu'au 16/08

on démarre mi octobre

nb de jours d'init à decider selon le nombre de site et le scope

- cloud privé
- déploiement **Capistrano** script déploiement sur notre gitlab

on le fait ensemble

- access admin mais pas root sur tout : il suffit de demander à Maxime
- tout sur notre **gitlab**
- commencer par un **Docker** installé pour comprendre le projet
- Redmine le notre ok = point d'entree unique
- **contrat** et **CGV** le notre

condition particulière pour la gestion de projet

projet Français (English pas encore mais faut voir)

interface de management maison => presentation partenaire a envoyer

ok pour aider a répondre aux appels d'offre

- Inauguration en octobre nouveau locaux

Referent TMA ok idem ticket et tel/sms

Redmine de Macaron

Réversibilité/transfert : 5 jours

formation au BO de Prestashop 1 jour ou 2 jours

hosting et infogérence

## **Blue&Blue [https://blueandblue.fr/](https://avogel.fr/)**

Blue&Blue relancé 1 an de prospection via agence superagency (qui a fait leur créa) encore un peu de SEO de ce groupe

TMA PrestaShop

pb hébergement OVH Y-1

connecté sur **nouvel ERP** et **import produits**

1 seul point d'entrée et si pb hosting en direct possible

sans engagement 5 jours puis renouvellent par avenant

si vous nous dites a l'avance c'est encore mieux organisé

en fonction de ce qui est consommé

(réduire ignite réduit si volume de TMA XX jours) => peu importe le nombre de jours

1 procédure automatisée de livraison identique preprod et prod : (pas une opération manuelle)

comment on livre en prod depuis preprod

capistrano script

=> gitlab déploiement auto => plutôt script qui monte une instance docker

& reverse MEP hebergeur?