# Administration d'une infrastructure Windows Server

## Description

Projet de mise en place d'une infrastructure Windows Server dans un environnement virtualisé.

Objectif :
Déployer et administrer un domaine Active Directory avec les services réseau essentiels.

## Technologies utilisées

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Group Policy Objects (GPO)
- VirtualBox / VMware
- Windows 10/11 Client

## Architecture

Serveur :
- Contrôleur de domaine : DC01
- Adresse IP : 192.168.1.10
- Domaine : entreprise.local

Client :
- Windows 11
- Membre du domaine entreprise.local

## Réalisations

### Active Directory
- Installation du rôle AD DS
- Promotion du serveur en contrôleur de domaine
- Création des utilisateurs et groupes

### DNS
- Configuration de la zone DNS
- Création des enregistrements nécessaires
- Résolution de noms interne

### DHCP
- Création d'une étendue DHCP
- Attribution automatique des adresses IP
- Configuration de la passerelle et DNS

### GPO
- Création de stratégies de sécurité
- Gestion des restrictions utilisateurs
- Application des stratégies aux OU

## Compétences démontrées

- Administration Windows Server
- Gestion des utilisateurs et groupes
- Services réseau
- Sécurité système
- Dépannage réseau
