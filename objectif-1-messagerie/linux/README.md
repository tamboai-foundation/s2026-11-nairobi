# Application Linux — Objectif 1 : Messagerie chiffrée & Chatbot

Ce dossier contient le code source et la documentation de l'application de messagerie instantanée chiffrée de bout en bout (avec chatbot intégré) développée pour **Linux** par notre équipe.

---

## Objectifs du module Linux
* Offrir une interface fluide sous Linux pour échanger des messages en temps réel.
* Garantir le chiffrement de bout en bout des conversations entre utilisateurs.
* Intégrer un assistant virtuel (chatbot) directement dans la messagerie.

---

## Structure du dossier (à compléter selon notre architecture)
```text
linux/
├── README.md        # Documentation principale de la plateforme Linux
├── src/             # Code source de l'application (interface, réseau, crypto, chatbot)
└── tests/           # Tests unitaires et tests d'intégration
```

---

## ⚙️ Installation et lancement en local

### 1. Prérequis
* Système d'exploitation : Distribution Linux (Ubuntu, Debian, Kali, Fedora, etc.)
* Outils de base : `git` et les outils de compilation/exécution adaptés à notre langage.
*(À compléter avec les dépendances exactes dès que la stack technique est figée).*

### 2. Récupérer le projet
```bash
git clone https://github.com
cd s2026-11-nairobi
git checkout develop
git pull
```

### 3. Compiler et exécuter
*(Les commandes exactes de compilation et de lancement seront ajoutées ici après l'initialisation du code source).*

---

## Règles de contribution pour l'équipe
1. Toujours partir de `develop` à jour : `git checkout develop && git pull`
2. Créer une branche dédiée : `git checkout -b objectif-1/<prenom>-<tache>`
3. Placer tout le code dans `objectif-1-messagerie/linux/`.
4. Ne jamais pousser de mots de passe, clés privées ou jetons API.
5. Ouvrir une **Pull Request** vers `develop` pour relecture par le Team Lead.
