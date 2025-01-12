# Conception-d-un-c-ur-de-r-seau-avec-gestion-avanc-e-des-services

# Conception d'un Cœur de Réseau avec Gestion Avancée des Services

## Table des matières
- [Description du Projet](#description-du-projet)
- [Technologies Utilisées](#technologies-utilisées)
- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Configuration](#configuration)
- [Machines Virtuelles](#machines-virtuelles)
- [Contributions](#contributions)
- [Licence](#licence)
- [Contact](#contact)

## Description du Projet
Ce projet consiste à concevoir une infrastructure réseau centralisée intégrant trois routeurs et quatre switchs pour interconnecter différents VLAN. Des machines virtuelles sous Linux et Windows ont été déployées pour fournir des services tels que DNS, DHCP et Active Directory. Un contrôleur LAN sans fil (WLC) a été mis en place pour gérer les points d'accès, assurant une connectivité Wi-Fi efficace.

## Technologies Utilisées
- **Routeurs** : 3 routeurs pour la gestion du trafic réseau.
- **Switchs** : 4 switchs pour l'interconnexion des VLAN.
- **Machines Virtuelles** : Utilisation de Linux et Windows pour les services.
- **Services** : DNS, DHCP, Active Directory.
- **Contrôleur LAN sans fil (WLC)** : Pour la gestion des points d'accès.

## Fonctionnalités
- Gestion centralisée des services réseau.
- Interconnexion de plusieurs VLAN pour une meilleure segmentation du réseau.
- Déploiement de services critiques (DNS, DHCP, Active Directory).
- Gestion efficace de la connectivité Wi-Fi via le contrôleur LAN sans fil.

## Installation
1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/adamchehade/Conception-d-un-c-ur-de-r-seau-avec-gestion-avanc-e-des-services.git
   cd votre-repo
Configurer les routeurs et switchs :

Suivez les instructions spécifiques pour la configuration de votre matériel.
Déployer les machines virtuelles :

Utilisez un hyperviseur (comme VMware ou VirtualBox) pour créer des machines virtuelles sous Linux et Windows.
Configurer les services :

Configurez DNS, DHCP et Active Directory sur les machines virtuelles selon vos besoins.
Configuration
Pour chaque routeur et switch, assurez-vous de définir les paramètres VLAN appropriés.
Configurez le contrôleur LAN sans fil pour connecter les points d'accès et gérer le trafic Wi-Fi.
Machines Virtuelles
Les machines virtuelles déployées dans ce projet incluent :

Linux VM : Fournit des services DNS et DHCP.
Windows VM : Fournit des services Active Directory.
Contributions
Les contributions sont les bienvenues ! Pour contribuer :

Fork le projet.
Créez une branche pour votre fonctionnalité (git checkout -b feature/nouvelle-fonctionnalité).
Committez vos modifications (git commit -m 'Ajout d'une nouvelle fonctionnalité').
Poussez votre branche (git push origin feature/nouvelle-fonctionnalité).
Ouvrez une pull request.
Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

Contact
Pour toute question, veuillez contacter :

Email : chehadeadam84@gmail.com



