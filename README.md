Configuration d'une infrastructure virtualisée avec VMware ESXi, Active Directory et Veeam Backup

📌 Introduction


Ce projet constitue la suite de l’exercice réalisé lors de la séance 7.
L’objectif est de mettre en place une infrastructure virtualisée comprenant :

VMware ESXi comme hyperviseur,

Active Directory pour la gestion centralisée des utilisateurs et l’authentification,

Veeam Backup pour assurer la protection et la restauration des données.

Une section supplémentaire a été ajoutée à la fin pour indiquer où prendre des captures d’écran afin de valider chaque étape de la configuration.


🎯 Objectifs du projet


Configurer une infrastructure réseau virtualisée sur VMware ESXi.

Intégrer Active Directory pour gérer les comptes utilisateurs et l’authentification.

Installer et configurer Veeam Backup & Replication pour sauvegarder les machines virtuelles.

Documenter le processus à l’aide de captures d’écran.

🛠️ Technologies et outils utilisés

VMware ESXi 8.x (hyperviseur bare-metal)

Windows Server (Active Directory Domain Services)

Veeam Backup & Replication

vSphere Client

Réseaux virtuels (NAT / Bridge / VMnet)


📂 Étapes principales


Configuration d’ESXi

Création et gestion des machines virtuelles.

Configuration réseau (NAT/Bridge).

Mise en place de l’Active Directory

Installation du rôle AD DS.

Création du domaine et intégration des utilisateurs.

Liaison entre ESXi et l’AD pour l’authentification.

Installation et configuration de Veeam Backup

Déploiement de Veeam sur une VM dédiée.

Ajout d’ESXi comme serveur géré dans Veeam.

Création et test de jobs de sauvegarde.

Validation et documentation

Vérification de la connectivité et de l’intégration AD.

Test de la sauvegarde avec Veeam.

Captures d’écran pour chaque étape clé présentes sur le fichier joins.

Connexion au vSphere Client.

Ajout du serveur ESXi dans Veeam Backup.

Configuration du rôle Active Directory (domaine créé).

Test de connexion avec un compte AD dans ESXi.

Job de sauvegarde Veeam réussi.


✅ Résultats attendus


À la fin de ce projet, vous devez avoir :

Un hyperviseur ESXi fonctionnel avec plusieurs VMs.

Un domaine Active Directory opérationnel et intégré à ESXi.

Un serveur Veeam Backup configuré et capable de sauvegarder vos VMs.

Une documentation illustrée par des captures d’écran.
