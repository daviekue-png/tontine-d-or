# TONTINE D'OR

Application Android de gestion de tontine, **100 % hors ligne**, avec
synchronisation facultative entre les téléphones des membres.

> Ce dépôt ne sert qu'à **distribuer l'application**. Il ne contient pas le code
> source, qui reste privé.

## Télécharger

**[Page de présentation](https://daviekue-png.github.io/tontine-d-or/)** — fonctions,
écrans, tarifs, questions fréquentes.

**[Télécharger la dernière version](https://github.com/daviekue-png/tontine-d-or/releases/latest/download/tontine-d-or.apk)**

- Android 7 et plus (téléphone ou tablette)
- APK universel : un seul fichier pour tous les appareils
- Aucun compte à créer sur ce site

Le lien `latest` pointe toujours vers la dernière version **validée**. Les
versions précédentes restent disponibles plus bas, dans « Releases ».

## Vérifier le fichier

L'empreinte SHA-256 de la version en cours est indiquée dans la note de la
Release et sur la page de présentation. Sous Windows :

```powershell
Get-FileHash .\tontine-d-or.apk -Algorithm SHA256
```

Sous Android, un gestionnaire de fichiers affichant les empreintes fait l'affaire.

## Premiers pas

1. Ouvrez le fichier téléchargé et acceptez « Installer des applications
   inconnues » pour votre navigateur si Android le demande.
2. Ouvrez TONTINE D'OR, créez votre compte (numéro de téléphone et mot de passe
   de 10 caractères minimum, lettres et chiffres).
3. Créez votre tontine, ou entrez dans une tontine existante avec le **code
   d'invitation** ou le **QR code** fourni par le bureau.
4. Essai gratuit de 30 jours, toutes les fonctions.

## Ce que fait l'application

- membres, fiches, photos facultatives, import d'une liste en une fois ;
- tours, cotisations, ordre de passage, clôture, bilan mensuel ;
- prêts, remboursements, pénalités, dépenses du groupe ;
- reçus PDF numérotés, relevés, exports Excel ;
- journal de sécurité : chaque saisie, modification et suppression est tracée
  avec son auteur ;
- quatre rôles (Super administrateur, Administrateur, Trésorier, Membre) et
  cloisonnement : chacun ne voit que ses tontines ;
- fonctionnement sans internet, synchronisation quand le réseau revient.

L'application **ne garde jamais l'argent des membres** : les fonds circulent en
espèces ou par mobile money. Elle ne fait ni pari, ni loterie, ni jeu d'argent.

## Mentions

Éditeur : TONTINE D'OR (Bénin). Les mentions légales complètes (dénomination,
RCCM, IFU, adresse) seront publiées dès l'immatriculation de l'éditeur ; aucune
donnée d'entreprise n'est affichée tant qu'elle n'est pas officielle.

Les données de synchronisation sont hébergées par Supabase (Amazon Web Services,
Union européenne) et ne sont lisibles que sous forme chiffrée.
