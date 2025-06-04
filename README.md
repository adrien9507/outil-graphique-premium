# 🎨 Outil Graphique Premium

Une suite d’outils créatifs modernes pour générer :
- Logos interactifs et par IA
- Fonds d’écran personnalisés
- Bannières de blog
- Créations futures (stories, cartes, citations, etc.)

---

## 📁 Contenu du projet

### Frontend
- `index.html` — Accueil de la suite
- `logo-creation.html` — Éditeur de logo + IA
- `wallpaper-personnalise.html` — Générateur de wallpaper + IA
- `bannieres-blog.html` — Générateur de bannières + IA
- `plus-encore.html` — Démo des outils à venir
- `style.css` — Thème moderne et minimaliste
- `script.js` — Comportements de base
- `hf-client.js` — Client IA Hugging Face (frontend)

### Backend IA
- `backend-hf-server.js` — Serveur Express pour requêtes IA
- `.env.example` — Clé API Hugging Face

---

## 🚀 Lancer en local

```bash
# Installez les dépendances backend
npm install express node-fetch dotenv

# Créez le fichier .env
cp .env.example .env
# Ajoutez votre HF_TOKEN (https://huggingface.co/settings/tokens)

# Lancez le backend
node backend-hf-server.js

# Puis ouvrez index.html dans un navigateur
```

---

## 🌐 Déploiement gratuit (Render)
1. Créez un compte : https://render.com
2. Créez un nouveau service web Node.js
3. Uploadez le dossier `outil-graphique-premium`
4. Ajoutez la variable d’environnement `HF_TOKEN`
5. Récupérez votre URL publique

---

## 🧠 Génération IA Hugging Face
- Basée sur le modèle `stabilityai/stable-diffusion-2`
- API : https://huggingface.co/inference-api

---

## ✨ Auteurs
- 💼 Vous (personnalisable)
- 🤖 Assistance technique : ChatGPT & Hugging Face
