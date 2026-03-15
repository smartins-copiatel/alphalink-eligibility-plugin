=== Alphalink Eligibility Form ===
Contributors: Copiatel
Tags: eligibility, fibre, alphalink, telecom
Requires at least: 5.0
Tested up to: 6.4
Stable tag: 3.2.0
License: Proprietary
License URI: https://copiatel.fr

Formulaire d'éligibilité Fibre/ADSL avec API Alphalink

== Description ==

Plugin WordPress professionnel pour tester l'éligibilité Fibre et ADSL via l'API Alphalink.

Fonctionnalités :
* Recherche d'adresse intelligente
* Détection automatique du numéro
* Suggestions de numéros proches
* Carte interactive Leaflet
* Informations réseau détaillées
* Affichage par fournisseur
* Responsive

== Installation ==

1. Uploadez le dossier dans `/wp-content/plugins/`
2. Activez le plugin
3. Configurez l'API dans Alphalink Cache → Configuration API
4. Ajoutez `[alphalink_eligibility]` dans une page

== Changelog ==

= 3.2.0 - 8 Mars 2026 =
* Version stable avec carte interactive
* Détection numéro automatique
* Numéros proches si inexistant
* Infos réseau (PM, NRA)
* Affichage par fournisseur

== Configuration ==

Allez dans Alphalink Cache → Configuration API :
- URL : https://ema.expert/ema/api/v1/
- Login : Fourni par Alphalink
- Clé API : Fournie par Alphalink

Votre IP serveur doit être whitelistée chez Alphalink.