# OutsideEat

**Plateforme de commande et de livraison de repas pour le Centre de Réadaptation de Mulhouse (CRM)**

> Statut : projet en cours de conception / développement. Les fonctionnalités présentées ci-dessous correspondent au cahier des charges et ne sont pas nécessairement déjà implémentées.

## Présentation

OutsideEat est un projet de site marchand destiné aux stagiaires, résidents et personnels du Centre de Réadaptation de Mulhouse (CRM).

Les utilisateurs pourront commander leurs repas et choisir entre une livraison dans les bâtiments autorisés du CRM (en chambre ou en salle de cours) et un retrait sur place en click & collect.

## Objectifs

- Proposer un service de restauration flexible et accessible.
- Réduire les files d'attente à la cafétéria.
- Améliorer le confort des résidents.
- Faciliter la gestion des commandes pour les restaurateurs et le CRM.

## Fonctionnalités prévues

### Utilisateurs

- Création de compte et connexion (email, SSO CRM ou numéro stagiaire, selon les intégrations retenues).
- Consultation des menus de la cafétéria.
- Personnalisation des plats : options, suppléments et allergies.
- Choix entre livraison en chambre, en salle de cours ou retrait sur place.
- Paiement en ligne : carte bancaire, portefeuille CRM et, si possible, tickets restaurant.
- Suivi des commandes en temps réel et consultation de l'historique.
- Notifications par email ou web ; SMS en option.

### Cafétéria

- Gestion des commandes en cours.
- Gestion des menus, stocks et disponibilités horaires.
- Création et gestion de promotions.
- Consultation des statistiques : ventes, plats populaires et heures de pointe.

### Livreurs

- Interface mobile pour consulter les livraisons à effectuer.
- Consultation des informations de livraison (chambre ou salle de cours).
- Confirmation des livraisons.

### Administration CRM

- Gestion des utilisateurs, la cafétéria et livreurs.
- Paramétrage des horaires, des zones de livraison et des tarifs.
- Accès à un tableau de bord global.

## Architecture et technologies envisagées

Le cahier des charges prévoit une application web responsive, conçue en mobile-first, reposant sur une API REST et une base de données centralisée.

Les technologies ci-dessous sont des options recommandées dans le cahier des charges, et non une stack technique définitivement choisie.

| Composant | Options envisagées |
| --- | --- |
| Front-end | React, Vue.js ou Angular |
| Back-end | Node.js, Django ou Laravel |
| Base de données | PostgreSQL ou MySQL |
| Hébergement | Azure, AWS ou OVH |
| Sécurité | HTTPS, chiffrement des données sensibles, conformité RGPD |

Stack définitive : à compléter par l'équipe après validation des choix techniques.

## Design et expérience utilisateur

L'interface devra être simple, intuitive et accessible, avec une navigation permettant de commander en quelques clics. Elle respectera la charte graphique du CRM.

Éléments prévus :
- Une page d'accueil mettant en avant les menus du jour.
- Des fiches détaillées pour chaque plat.
- Un panier visible en permanence.
- Le suivi des commandes en temps réel.
- Un affichage adapté aux mobiles, tablettes et ordinateurs.

## Contraintes et exigences

- Livraison limitée aux bâtiments autorisés du CRM.
- Gestion des créneaux horaires pour limiter les surcharges.
- Contrôle des stocks afin d'éviter les surcommandes.
- Objectif de temps de réponse inférieur à 2 secondes.
- Objectif de disponibilité d'au moins 99 %.
- Respect du RGPD, conservation des données de transaction et présence de CGU et mentions légales.

Ces objectifs et exigences devront être vérifiés au cours du développement et des tests.
**Rajout éventuel d'options supplémenataires : restaurants partenaires.** 

## Planning prévisionnel

| Phase | Durée estimée |
| --- | --- |
| Analyse et conception (ateliers, maquettes, architecture) | Environ 3 semaines |
| Développement front-end et back-end | 6 à 10 semaines |
| Tests et corrections | 2 à 3 semaines |
| Déploiement | 1 semaine |
| Formation des restaurateurs et livreurs | 1 semaine |

*Les durées sont prévisionnelles et peuvent évoluer.*

## Livrables attendus

- [ ] Maquettes UX/UI
- [ ] Code source complet
- [ ] Documentation technique et utilisateur
- [ ] Tableau de bord administrateur
- [ ] Version finale déployée et fonctionnelle

> Les cases sont volontairement non cochées : l'état d'avancement réel est à renseigner par l'équipe.

## Installation et lancement

Les instructions d'installation seront ajoutées après validation de la stack technique et de la structure du dépôt.

À compléter : prérequis, configuration de l'environnement, installation des dépendances, configuration de la base de données et commandes de démarrage.

## Équipe et contribution

Les membres de l'équipe, les rôles et les règles de contribution seront précisés au fur et à mesure du projet.

## Documentation

Ce README présente les grandes lignes du cahier des charges OutsideEat, version 1.0.0. Pour les spécifications détaillées, consulter le cahier des charges du projet.
