# Calciplan

Un calculateur d'apport calcique quotidien.

## À propos

Calciplan est une application web simple qui permet de calculer la quantité de calcium consommée à chaque repas et sur une journée complète.

### Fonctionnalités

- Sélection des quantités d'aliments riches en calcium à travers différents repas
- Calcul automatique des totaux par repas et journalier
- Sauvegarde locale des données dans le navigateur

## Développement

C'est une application web statique, sans processus de build :
- HTML / CSS / JavaScript vanilla
- Tout le code est contenu dans le fichier `index.html`

## Déploiement

L'application est déployée sur Vercel, connecté au dépôt GitHub.

### Instructions de déploiement

1. Pusher les changements sur GitHub
2. Vercel détecte automatiquement les changements et redéploie l'application
3. L'application est accessible à l'adresse : https://calciplan.vercel.app

## Améliorations futures

- Ajout d'un favicon et d'un manifest pour en faire une PWA installable
- Implémentation d'une fonction d'export CSV ou de partage
- Ajout d'une sauvegarde multi-utilisateur (avec Firebase ou Supabase)