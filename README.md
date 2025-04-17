# Portfolio – Mehdi Nour

Bienvenue dans mon portfolio professionnel de **Data Scientist**, développé avec **Astro** et hébergé via **GitHub Pages**.

## 🔍 Aperçu

Ce site présente mon parcours, mes compétences, mes expériences et mes intérêts dans le domaine de la **data science**, de l'**IA**, du **cloud** et de la **visualisation**.

📍 **Démo en ligne** : [https://mnour01.github.io/my-portfolio/](https://mnour01.github.io/my-portfolio/)

---

## 🛠️ Structure du projet

Voici les différentes pages disponibles sur le site :

- `index.astro` → Page d'accueil avec photo + présentation
- `experiences.astro` → Expérience professionnelle complète
- `formations.astro` → Diplômes et parcours académique
- `competences.astro` → Compétences techniques détaillées
- `langues.astro` → Langues parlées
- `interets.astro` → Centres d’intérêt personnels

---

## 📁 Arborescence

```
my-portfolio/
├── public/
│   └── images/ → contient les photos (ex : pdp_mehdi.png)
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       ├── index.astro
│       ├── experiences.astro
│       ├── formations.astro
│       ├── competences.astro
│       ├── langues.astro
│       └── interets.astro
├── astro.config.mjs
├── package.json
└── README.md ← (ce fichier)
```

---

## 🚀 Installation et déploiement

### 1. Cloner le projet

```bash
git clone https://github.com/mnour01/my-portfolio.git
cd my-portfolio
```

### 2. Installer les dépendances

```bash
npm install
```

### 3. Lancer le site en local

```bash
npm run dev
```

Puis accéder au site sur : `http://localhost:4321/my-portfolio/`

### 4. Préparer le build

```bash
npm run build
```

### 5. Déployer vers GitHub Pages

Assurez-vous que dans `astro.config.mjs`, le `base` est bien défini :

\```js
import { defineConfig } from 'astro/config';

export default defineConfig({
  base: "/my-portfolio/",
});
\```

Puis lancez :

```bash
npm run deploy
```

> Le site sera alors disponible sur : [https://mnour01.github.io/my-portfolio/](https://mnour01.github.io/my-portfolio/)

---

## 🔁 Bonnes pratiques

- Toutes les images doivent être placées dans le dossier `public/images/`.
- Les liens internes utilisent `/my-portfolio/nom-de-la-page` comme chemin.
- Le design est **responsive**, orienté **tech / high-tech**, avec un code **modulaire** basé sur `BaseLayout`.

---

## 🧠 Auteur

**Mehdi Nour**  
📧 nour.mehdi@yahoo.com  
💼 [LinkedIn](https://linkedin.com/in/nour-mehdi)

&copy; 2025 — Projet personnel

---
