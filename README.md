<div align="center">

<img src="https://drive.google.com/uc?export=view&id=1q8AH8RTJTGsBn5JJkHoM3R_MC1Y-dN4O" alt="InboxCleaner Logo" width="100">

# InboxCleaner

**Nettoyez votre boîte Gmail en quelques clics.**

Supprimez les mails indésirables par ancienneté, mots-clés ou expéditeur.
Gratuit, open source, et vos emails ne quittent jamais votre compte Google.

[![Installer depuis le Marketplace](https://img.shields.io/badge/Google%20Workspace-Installer-4285F4?style=for-the-badge&logo=google)](https://workspace.google.com)
[![Soutenir sur Tipeee](https://img.shields.io/badge/Tipeee-Soutenir%20le%20projet-F06292?style=for-the-badge)](https://www.tipeee.com/cryptex)

</div>

---

## C'est quoi InboxCleaner ?

InboxCleaner est un module complémentaire Gmail qui vous permet de faire le ménage dans votre boîte mail sans effort. Plus besoin de supprimer les mails un par un : vous choisissez vos critères, vous prévisualisez le résultat, et vous nettoyez en un clic.

Le script tourne entièrement dans votre propre compte Google. Aucune donnée ne passe par un serveur externe, aucune information n'est collectée.

---

## Fonctionnalités

**Nettoyage par ancienneté**
Déplacez à la corbeille tous les mails plus vieux que 7 jours, 30 jours, 6 mois, 1 an ou 2 ans.

**Nettoyage par mots-clés**
Ciblez les mails dont l'objet ou le corps contient certains mots : "newsletter", "promotion", "unsubscribe"...

**Nettoyage par expéditeur**
Supprimez tous les mails provenant d'une adresse précise : noreply@site.com, offers@shop.com...

**Mode aperçu**
Avant de supprimer quoi que ce soit, visualisez combien de conversations seraient concernées.

**Sécurités intégrées**
Les mails étoilés et les mails envoyés sont toujours préservés, quoi qu'il arrive.

---

## Installation

> Aucune compétence technique requise. L'installation prend moins de 2 minutes.

1. Cliquez sur le bouton **Installer depuis le Marketplace** en haut de cette page
2. Connectez-vous avec votre compte Google
3. Autorisez les permissions demandées
4. Ouvrez Gmail : InboxCleaner apparaît dans le panneau latéral droit

C'est tout.

---

## Comment ça marche ?

InboxCleaner est un Google Apps Script, c'est-à-dire un script officiel qui tourne directement dans votre compte Google, sur les serveurs de Google. Il utilise l'API Gmail officielle pour rechercher et déplacer vos mails.

Concrètement :

- Le script ne connaît pas votre mot de passe
- Aucun email n'est lu ou stocké par InboxCleaner
- Les mails sont déplacés à la corbeille (pas supprimés définitivement : Gmail les purge automatiquement après 30 jours)
- Vous pouvez vérifier le code source vous-même, il est entièrement visible ici

---

## Vie privée et sécurité

InboxCleaner ne collecte aucune donnée personnelle. Le script s'exécute localement dans votre compte Google.

Permissions utilisées :

- `gmail.modify` : pour déplacer les mails vers la corbeille
- `gmail.readonly` : pour rechercher les mails (mode aperçu)
- `gmail.addons.execute` : pour faire fonctionner le module complémentaire

Ces permissions peuvent être révoquées à tout moment depuis [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

Politique de confidentialité complète : [cryptexhq.github.io/inboxcleaner/privacy-policy](https://cryptexhq.github.io/inboxcleaner/privacy-policy)

---

## Soutenir le projet

InboxCleaner est gratuit et le restera. Si il vous fait gagner du temps, un petit don est toujours apprécié et permet de continuer à développer des outils utiles.

[☕ Soutenir sur Tipeee](https://www.tipeee.com/TON_PROFIL)

Les donateurs dont le pseudo apparaît ci-dessous ont rendu ce projet possible :

*Soyez le premier à soutenir InboxCleaner.*

---

## Développé par

**Cryptex** : audit de sécurité web, pentest et développement sur mesure pour PME belges.

[cryptexhq.github.io](https://cryptexhq.github.io)

---

## Licence

Ce projet est distribué sous licence MIT. Vous êtes libre de l'utiliser, le modifier et le redistribuer.

Voir le fichier [LICENSE](LICENSE) pour les détails.# InboxCleaner
Nettoyez votre boîte Gmail en quelques clics. Supprimez les mails indésirables par ancienneté, mots-clés ou expéditeur. Simple, rapide, 100% sécurisé.
