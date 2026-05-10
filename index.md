# Politique de confidentialité — VITAL I.A

**Dernière mise à jour : 10/05/2026** · Version 1.5.65

> 📄 La version complète et détaillée (CGU + Politique RGPD + Avertissement médical, 17 sections) est disponible à l'adresse :
> **<https://olivieronno-svg.github.io/bilanambu/privacy.html>**
>
> Cette page maintient une version courte pour les anciens liens.

---

## Préambule

VITAL I.A (anciennement BilanAmbu) est un assistant médical pédagogique qui combine des tutoriels guidés par I.A et des outils cliniques (RCP/DAE, ECG, bilan ambulancier, scores cliniques, autonomie O₂…).

L'application **n'est pas un dispositif médical** au sens du Règlement européen 2017/745. Elle ne remplace ni le jugement clinique, ni une formation officielle aux premiers secours (PSC1, AFGSU, PSE), ni les protocoles de votre service.

Cette politique décrit les données traitées, leur finalité, leur durée de conservation et les droits de l'utilisateur.

## 1. Responsable du traitement

L'utilisateur de l'application est le seul responsable des données qu'il y saisit, dans le cadre de son usage personnel d'aide à la rédaction de bilans pré-hospitaliers ou de pratique des gestes d'urgence.

L'éditeur de l'application (Onn-Off Studio) **n'a accès à aucune donnée saisie**.

## 2. Données traitées

L'application traite les catégories de données suivantes lorsque l'utilisateur les renseigne :

- **Données d'identification du patient** : nom, prénom, âge, sexe, poids, adresse, médecin traitant, personne à prévenir
- **Données de santé** : constantes vitales, scores cliniques (Glasgow, ABSI, APGAR, Lund-Browder, MNA, Malinas, déshydratation), antécédents, traitements, allergies, observations de l'examen clinique, informations relatives à la grossesse, au nouveau-né, à la réanimation cardio-pulmonaire
- **Données métier** : circonstances de l'événement, gestes effectués, destination, paramètres de transport
- **Préférences applicatives** : email destinataire par défaut, bouteille O₂ par défaut, langue, mode d'affichage, pays de détection

L'application demande les autorisations Android suivantes :

- **Localisation** (`ACCESS_FINE_LOCATION`) : uniquement pour la recherche des défibrillateurs (DAE) et hôpitaux à proximité, à la demande de l'utilisateur
- **Microphone** (`RECORD_AUDIO`) : uniquement pour la dictée vocale et le mode guidé I.A des tutos. Aucun enregistrement audio n'est conservé
- **Téléphone** (`CALL_PHONE`) : uniquement pour le bouton « Appeler le SAMU » qui compose directement le numéro d'urgence local. Aucun appel n'est passé sans action explicite de l'utilisateur
- **Internet** : pour les requêtes OpenStreetMap (POI), l'envoi de PDF par email, et les achats Play Billing
- **Vibration** : retour haptique du compteur de fréquence cardiaque/respiratoire

## 3. Stockage et hébergement

**Toutes les données sont stockées localement sur l'appareil de l'utilisateur**, dans une base SQLite (Room) chiffrée par le système Android (Full-Disk Encryption activé par défaut sur Android 7+).

**Aucune donnée n'est transmise à un serveur de l'éditeur** par l'application elle-même. Aucun SDK tiers (Firebase Analytics, Crashlytics, etc.) n'est intégré.

L'application bénéficie de la sauvegarde automatique Android (Google Drive du compte de l'utilisateur), si celle-ci est activée dans les paramètres système. Cette sauvegarde est configurée par l'utilisateur, sous sa responsabilité.

## 4. Services tiers

- **Google Play Billing** (Google LLC) : pour l'abonnement Premium. Les données de paiement ne transitent pas par l'éditeur. Voir la [politique de Google](https://policies.google.com/privacy).
- **OpenStreetMap Overpass API** : pour la recherche des défibrillateurs et hôpitaux. La position de l'utilisateur est envoyée à l'API publique Overpass uniquement pendant la recherche.
- **Synthèse vocale Android (TextToSpeech)** : pour le mode guidé I.A des tutos. Aucune donnée audio n'est transmise.

## 5. Transmission des fiches

L'utilisateur peut, à sa demande explicite via le bouton « Envoyer par mail », générer un PDF de la fiche bilan et l'expédier via l'application e-mail tierce de son choix. Cette transmission est sous la responsabilité de l'utilisateur.

## 6. Durée de conservation

Les fiches sont conservées sur l'appareil tant que l'utilisateur ne les supprime pas. La désinstallation de l'application supprime l'ensemble des données.

Les PDF générés sont conservés temporairement dans le cache de l'application et sont supprimés automatiquement au-delà de 7 jours.

## 7. Droits de l'utilisateur (RGPD)

L'utilisateur peut à tout moment :

- Accéder aux fiches enregistrées (écran « Historique »)
- Modifier les données saisies
- Supprimer une fiche individuellement
- Désinstaller l'application pour effacer l'ensemble des données
- Désactiver les permissions Android (paramètres système)
- Désactiver la bande son d'introduction (Réglages de l'application)

## 8. Mineurs

L'application n'est pas destinée à un usage par des mineurs. Aucune donnée personnelle n'est collectée auprès de mineurs.

## 9. Modifications

Toute modification de cette politique sera publiée à la même URL. La date de dernière mise à jour figure en tête du document.

## 10. Contact

Pour toute question relative à cette politique :
**onnoff1975@gmail.com**

Éditeur : **Onn-Off Studio**

---

📄 Pour la version complète (CGU + Politique + 17 sections) : <https://olivieronno-svg.github.io/bilanambu/privacy.html>
