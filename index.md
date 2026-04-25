# Politique de confidentialité — BilanAmbu

**Dernière mise à jour : 25/04/2026**

## Préambule

BilanAmbu est un outil personnel de saisie de bilan ambulancier. Il ne dispense pas du jugement clinique et **n'est pas un dispositif médical** au sens de la réglementation européenne (RIM 2017/745).

Cette politique décrit les données traitées, leur finalité, leur durée de conservation et les droits de l'utilisateur.

## 1. Responsable du traitement

L'utilisateur de l'application est le seul responsable des données qu'il y saisit, dans le cadre de son usage personnel d'aide à la rédaction de bilans pré-hospitaliers.

L'éditeur de l'application n'a accès à aucune donnée saisie.

## 2. Données traitées

L'application traite les catégories de données suivantes lorsque l'utilisateur les renseigne :

- **Données d'identification du patient** : nom, prénom, âge, sexe, poids, adresse, médecin traitant, personne à prévenir
- **Données de santé** : constantes vitales, scores cliniques (Glasgow, ABSI, APGAR, Lund et Browder), antécédents, traitements, allergies, observations de l'examen clinique, informations relatives à la grossesse, au nouveau-né, à la réanimation cardio-pulmonaire
- **Données métier** : circonstances de l'événement, gestes effectués, destination, paramètres de transport
- **Préférences applicatives** : email destinataire par défaut, bouteille O2 par défaut, mode d'affichage

L'application demande les autorisations Android suivantes :
- **Microphone** (`RECORD_AUDIO`) : uniquement pour la dictée vocale, à la demande explicite de l'utilisateur sur chaque champ. Aucun enregistrement audio n'est conservé.
- **Téléphone** (`CALL_PHONE`) : uniquement pour le bouton « Appeler le 15 » qui compose directement le numéro du SAMU. Aucun appel n'est passé sans action de l'utilisateur.
- **Internet** : uniquement pour permettre l'envoi du PDF généré par l'application e-mail tierce choisie par l'utilisateur.
- **Vibration** : retour haptique du compteur de fréquence respiratoire.

## 3. Stockage et hébergement

**Toutes les données sont stockées localement sur l'appareil de l'utilisateur**, dans une base SQLite chiffrée par le système Android (Full-Disk Encryption activé par défaut sur Android 7+).

**Aucune donnée n'est transmise à un serveur tiers** par l'application elle-même.

L'application bénéficie de la sauvegarde automatique Android (Google Drive du compte de l'utilisateur), si celle-ci est activée dans les paramètres système du téléphone. Cette sauvegarde est configurée par l'utilisateur, sous sa responsabilité.

L'application ne pratique aucun hébergement HDS (Hébergeur de Données de Santé) puisqu'aucune donnée ne quitte l'appareil par son intermédiaire.

## 4. Transmission des fiches

L'utilisateur peut, à sa demande explicite via le bouton « Envoyer par mail », générer un PDF de la fiche bilan et l'expédier via l'application e-mail tierce de son choix. Cette transmission est sous la responsabilité de l'utilisateur.

## 5. Durée de conservation

Les fiches sont conservées sur l'appareil tant que l'utilisateur ne les supprime pas. La désinstallation de l'application supprime l'ensemble des données.

Les PDF générés sont conservés temporairement dans le cache de l'application et sont supprimés automatiquement au-delà de 7 jours.

## 6. Droits de l'utilisateur

L'utilisateur peut à tout moment :
- Accéder aux fiches enregistrées (écran « Historique »)
- Modifier les données saisies
- Supprimer une fiche individuellement
- Désinstaller l'application pour effacer l'ensemble des données

## 7. Mineurs

L'application n'est pas destinée à un usage par des mineurs. Aucune donnée personnelle n'est collectée auprès de mineurs.

## 8. Modifications

Toute modification de cette politique sera publiée à la même URL. La date de dernière mise à jour figure en tête du document.

## 9. Contact

Pour toute question relative à cette politique :
onnoff1975@gmail.com
