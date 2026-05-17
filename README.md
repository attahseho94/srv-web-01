# 🚀 Projet SISR - Serveur Web Apache (srv-web-01)

# 🎯 Objectif

Créer un serveur web sous Linux avec Apache dans une machine virtuelle afin de comprendre :

* la virtualisation
* Linux
* les services réseau
* l’administration système

---

# 🧰 Environnement utilisé

* VirtualBox
* Ubuntu Server
* Apache2
* Windows hôte

---

# 🏗️ Architecture

PC Windows
→ VirtualBox
→ Ubuntu Server
→ Apache Web Server
→ Page web accessible via navigateur

---

# 🌐 Configuration réseau

* Mode : Accès par pont (Bridged)
* IP du serveur : 192.168.x.x

---

# ⚙️ Installation Apache

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install apache2 -y
```

---

# 📄 Page web

Page accessible via :

http://192.168.x.x

---

# 🧠 Compétences acquises

* Linux (Ubuntu Server)
* Virtualisation
* Réseau local
* Apache Web Server
* Administration système
* Dépannage

---

# 📸 Preuves

Captures disponibles dans le dossier screenshots/ ou
![Apache](screenshots/apache.png.png)

---

# 👨‍💻 Auteur

Projet réalisé dans le cadre de l’apprentissage BTS SIO SISR
