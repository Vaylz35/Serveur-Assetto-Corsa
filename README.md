# Serveur Assetto Corsa - Installation Debian 12 (amd64)

Ce paquet permet d’installer automatiquement un serveur dédié Assetto Corsa ainsi que son interface de gestion.

---

## 📌 Prérequis

- Debian 12.10 (amd64)
- Accès root ou sudo
- Connexion internet active

---

## ⚙️ Installation

### 1. Mise à jour du système
```bash
apt update && apt upgrade -y
```

### 2. Téléchargement du paquet
```bash
wget https://raw.githubusercontent.com/Vaylz35/Serveur-Assetto-Corsa/main/ns-ac.deb
```

### 3. Installation du serveur
```bash
apt install ./ns-ac.deb
```

## 🌐 Accès à l’interface

Une fois l’installation terminée, l’interface web est accessible à l’adresse suivante :

- http://localhost:8772

> Si le serveur est installé sur une machine distante, remplacer `localhost` par l’adresse IP du serveur.

---

## 🔐 Identifiants par défaut

- Utilisateur : `admin`
- Mot de passe : `servermanager`

> Il est recommandé de modifier ces identifiants après la première connexion.
