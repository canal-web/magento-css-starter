# Notice du Starter

## Les documents à récuperer 
* Positionnez tout ou une partie des documents qui vous interessent dans /scss/starter
* Rendez-vous dans styles.scss pour associer les documents en question sur ce modèle : 
    * @import 'starter/variablesmixin';
    * @import 'starter/compte';
    * @import 'starter/panier';
    * @import 'starter/menu';
    * @import 'starter/general';
    * @import 'starter/connexioncompte';
    * @import 'starter/messages';
    * @import 'starter/panier-desktop';

### Récuperer les documents

###Liste des documents
* **general.scss** : tout ce qui est commun à tous les sites, possibilité de changer l'aspect des input et select ainsi que les tailles de polices en fonction des résolutions
* **_connexioncompte.scss** : uniquemement la page de connexion
* **_compte.scss** : concerne toute la partie compte une fois connecté ainsi que la page d'inscription et le mot de passe oublié
* **_messages.scss** : tous les messages d'erreur et de réussite
* **_panier.scss** : processus panier, checkout et panier du menu
* **_menu-mobile.scss**: uniquement le menu mobile
* **_panier-desktop.scss**: uniquement le panier desktop

## Le document _variablesmixin.scss

Avant de commencer, vérifier l'ensemble des variables et des mixin de ce document pour les adapter à la charte du site.

### Les mixins

* **Les trois styles de titres** : h1, h2, h3 à adapter en fonction de la charte
* **Les transitions** : qui en général ne changent pas
* **Les boutons principaux** : les plus visibles
* **Les boutons secondaires** : en mineur, soit ghost, soit couleur moins visible, soit plus petits
* **Textes en gras** : mixin au cas où il n'existe pas de font grasse 

### Les variables
* **$starter_maincolor** : la couleur principale du site
* **$starter_background-color** : la couleur de fond foncée des tableaux
* **$starter_mainfont** : la typographie principale du site
* **$max-width** : la taille maximale du container du site, il faut reprendre celle utilisée dans le document grid.scss
* **$starter_reussite** : couleur des messages de réussite
* **$starter_erreur** : couleur des messages d'erreur

## Dans les autres documents 

### Les options
* Possibilité de changer la couleur des SVG dans images

## Ne pas oublier
* Mettre le module qui ajoute des class en fonction du navigateur et du support
* ~~Supprimer les entrées de menu inutiles "Biling agreements", "Recurring profiles", "My tags", "My applications", "My downloadable products"~~
* ~~Ajouter un lien de déconnexion~~
* Mettre le bloc "My orders" dans la colonne de gauche
