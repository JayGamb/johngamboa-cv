# CV - John Gamboa Alegria

Un site CV minimaliste style Notion, conçu pour être hébergé sur GitHub Pages.

## 🎨 Caractéristiques

- **Design minimaliste** inspiré de Notion
- **Mode sombre/clair** avec persistance
- **Responsive** (mobile, tablette, desktop)
- **Animations subtiles** et interactions fluides
- **Optimisé pour l'impression**
- **Accessibilité** (navigation clavier, focus visible)

## 🚀 Déploiement sur GitHub Pages

### 1. Créer un repository GitHub

1. Allez sur [GitHub](https://github.com) et créez un nouveau repository
2. Nommez-le `your-username.github.io` (remplacez `your-username` par votre nom d'utilisateur)
3. Rendez-le public

### 2. Pousser le code

```bash
# Initialiser Git (si pas déjà fait)
git init

# Ajouter tous les fichiers
git add .

# Premier commit
git commit -m "Initial commit: CV minimaliste style Notion"

# Ajouter le remote GitHub
git remote add origin https://github.com/your-username/your-username.github.io.git

# Pousser vers GitHub
git push -u origin main
```

### 3. Activer GitHub Pages

1. Allez dans les **Settings** de votre repository
2. Scroll jusqu'à la section **Pages**
3. Dans **Source**, sélectionnez **Deploy from a branch**
4. Choisissez la branche **main** et le dossier **/(root)**
5. Cliquez **Save**

Votre site sera disponible à `https://your-username.github.io`

## 📁 Structure du projet

```
my-cv/
├── index.html          # Page principale
├── styles/
│   └── main.css        # Styles CSS
├── scripts/
│   └── main.js         # JavaScript
├── assets/
│   └── images/         # Images (optionnel)
└── README.md           # Documentation
```

## 🛠️ Personnalisation

### Modifier les informations

Éditez le fichier `index.html` pour changer :
- Nom et coordonnées
- Expérience professionnelle
- Compétences
- Formations
- Centres d'intérêt

### Modifier le style

Le fichier `styles/main.css` contient :
- Variables CSS pour les couleurs
- Styles responsive
- Animations et transitions

### Ajouter des fonctionnalités

Le fichier `scripts/main.js` gère :
- Basculement thème clair/sombre
- Animations au scroll
- Interactions utilisateur

## 🎯 Fonctionnalités

- **Mode sombre/clair** : Bouton en haut à droite
- **Copie email** : Cliquez sur l'email pour le copier
- **Animations** : Sections qui apparaissent au scroll
- **Responsive** : S'adapte à tous les écrans
- **Impression** : Optimisé pour l'impression

## 🔧 Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles modernes avec variables CSS
- **JavaScript vanilla** : Interactions et animations
- **Google Fonts** : Typographie Inter
- **GitHub Pages** : Hébergement gratuit

## 📱 Compatibilité

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile (iOS/Android)

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier selon vos besoins.

---

**Créé avec ❤️ pour un CV moderne et professionnel** 