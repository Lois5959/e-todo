# E-Todo

E-Todo est une application web de gestion de tâches (todo list) fullstack.  
Elle permet d'ajouter, consulter et supprimer des tâches, avec une base de données MySQL et une interface frontend moderne.

---

## Technologies utilisées

- **Backend :** Node.js, Express
- **Base de données :** MySQL (Docker)
- **Frontend :** Vite, JavaScript
- **Gestion des dépendances :** npm
- **Outils :** Docker, dotenv, PhpMyAdmin

---

## Fonctionnalités

- Ajouter de nouvelles tâches
- Marquer des tâches comme terminées
- Supprimer des tâches
- Stockage persistant des données avec MySQL
- Interface web simple et réactive
- Administration facile via PhpMyAdmin

---

## Installation complète

Installer Docker et Docker Compose:
docker --version
docker compose version

Lancer la base de données et le backend avec Docker:
docker compose up --build

Installer et lancer le frontend:
cd frontend
npm install
npm run dev

---

### 1️⃣ Cloner le projet
```bash
git clone <URL_DE_TON_REPO>
cd e-todo
