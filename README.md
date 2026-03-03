# Politique de confidentialite - VerifMot+

Derniere mise a jour : 3 mars 2026

## 1) Portee

La presente politique de confidentialite s'applique a l'application Android **VerifMot+** (package : `com.verifmotplus.app`).

## 2) Responsable du traitement

- Nom de l'application : VerifMot+
- Editeur : Asashiin
- Contact : asashiin2@gmail.com

## 3) Donnees traitees

VerifMot+ fonctionne principalement hors ligne.

### 3.1 Mots saisis par l'utilisateur

- Nature : mots saisis pour verifier leur validite, rechercher une definition ou consulter une conjugaison.
- Finalite : fournir les fonctionnalites principales de l'application.
- Lieu de traitement : localement sur l'appareil.
- Transmission a l'editeur : **Non**.

### 3.2 Historique local (dans l'application)

- Nature : mot verifie, resultat (valide/invalide), horodatage.
- Finalite : afficher l'ecran "Historique" (jusqu'a 20 entrees recentes).
- Lieu de traitement : etat local de l'application.
- Transmission a l'editeur : **Non**.

Important : cet historique n'est pas un service cloud ni un compte utilisateur.

### 3.3 Ressources dictionnaire/conjugaison locales

- Nature : listes de mots integrees et base SQLite locale necessaires au fonctionnement hors ligne.
- Finalite : fournir les fonctions dictionnaire et conjugaison.
- Lieu de stockage : espace prive de l'application sur l'appareil.
- Transmission a l'editeur : **Non**.

## 4) Donnees non collectees

VerifMot+ ne demande pas et n'utilise pas de permissions sensibles au runtime pour :

- la localisation
- les contacts
- la camera
- le microphone
- les SMS et journaux d'appels
- la galerie photo / les medias

VerifMot+ ne propose pas de creation de compte ni d'authentification.

## 5) Services tiers

VerifMot+ contient un bouton de don volontaire ouvrant PayPal dans le navigateur de l'utilisateur :

- `https://www.paypal.com/donate/?token=xv8d5UfU0G_NO9KXsyaFbQJiOpuIOQK_7CZMyW1A6ryKz2FFvGfCvYlfYx-fv1unlMpqI-zz2BeVv9ts&locale.x=fr_FR`

Le don est ponctuel, facultatif et n'est soumis a aucune obligation.
Il s'agit uniquement d'un moyen d'offrir un soutien au projet.
Quand l'utilisateur clique sur ce bouton, il quitte l'application et est soumis a la politique de confidentialite et aux conditions de PayPal.

## 6) Sauvegarde Android et transfert d'appareil

Le manifeste active les mecanismes de sauvegarde Android (`android:allowBackup="true"`). Selon les reglages du terminal et le comportement du systeme Android/Google, certains fichiers de l'application peuvent etre inclus dans les sauvegardes systeme ou les transferts d'appareil.

Il s'agit d'un mecanisme plateforme. VerifMot+ n'exploite pas de serveur de sauvegarde distant propre.

## 7) Partage et vente de donnees

- Aucune donnee personnelle n'est vendue.
- Les mots saisis et l'historique ne sont pas partages avec un backend editeur (aucun backend de ce type n'est utilise par l'application pour ces fonctions).

## 8) Conservation et suppression

- L'historique dans l'application est limite aux entrees recentes et destine a un usage local.
- Les donnees locales peuvent etre supprimees en :
  - vidant le stockage de l'application dans les reglages Android
  - desinstallant l'application

## 9) Securite

L'application privilegie le traitement local et la sandbox Android pour les donnees stockees sur l'appareil.
Aucune methode ne garantit une securite absolue, mais VerifMot+ limite l'exposition en evitant la collecte et la transmission non necessaires.

## 10) Mineurs

VerifMot+ est une application utilitaire linguistique et n'est pas concue pour collecter intentionnellement des donnees personnelles de mineurs.

## 11) Modifications de cette politique

Cette politique peut etre mise a jour pour refleter les evolutions de l'application, les exigences legales ou les exigences des plateformes.
La date "Derniere mise a jour" indique la version en vigueur.

## 12) Contact

Pour toute question relative a la confidentialite :

- Email : asashiin2@gmail.com

---

## References Google Play

Google Play exige un lien public vers une politique de confidentialite claire et accessible.

- User Data policy : https://support.google.com/googleplay/android-developer/answer/10144311
- Developer Program Policy (Privacy/User Data) : https://support.google.com/googleplay/android-developer/answer/16852659

