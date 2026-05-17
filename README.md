# srv-web-01
Premier pat avec VirtualBox / Ubuntu Server
# Projet SISR - Serveur Web Linux Apache

 ## Objectif

Créer un serveur web Linux dans une machine virtuelle avec Apache afin d'apprendre :

* la virtualisation,
* Linux,
* le réseau,
* les services web,
* l'administration système.

---

 Environnement utilisé

* Windows
* VirtualBox
* Ubuntu Server
* Apache2

---

## Architecture

PC Windows
→ VirtualBox
→ VM Ubuntu Server
→ Apache Web Server

---

## Étapes réalisées

### 1. Création de la machine virtuelle

* Installation de VirtualBox
* Création de la VM `srv-web-01`
* Allocation RAM et stockage

### 2. Installation Ubuntu Server

* Création utilisateur Linux
* Installation OpenSSH
* Mise à jour système

### 3. Configuration réseau

* Passage du réseau VirtualBox en mode pont
* Attribution d'une IP locale

Adresse IP du serveur :
`192.168.1.97`

### 4. Installation Apache

Commande utilisée :

bash
sudo apt install apache2 -y


Vérification du service :

bash
systemctl status apache2


---

## Résultat

Le serveur web est accessible depuis le navigateur :

text
http://192.168.1.97


Affichage de la page Apache par défaut.

---

## Compétences travaillées

* Linux
* Virtualisation
* Réseau
* Apache
* Administration système
* Dépannage
* Utilisation du terminal

---

## Difficultés rencontrées

### Virtualisation désactivée dans le BIOS

Erreur rencontrée :

* VT-x disabled

Solution :

* activation de la virtualisation dans le BIOS.

### Accès réseau à la VM

Problème :

* serveur inaccessible depuis Windows.

Solution :

* configuration réseau VirtualBox en mode pont.

---

## Auteur

Projet réalisé dans le cadre de l'apprentissage BTS SIO SISR.
