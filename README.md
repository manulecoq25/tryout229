# 🐾 MyPet360 — Soin complet pour votre animal au Bénin

> Téléconsultation vétérinaire · Dog Walking · Garde & Hébergement · Boutique en ligne

Site web vitrine / démo client — déployable sur GitHub Pages en moins de 5 minutes.

---

## 🚀 Déploiement sur GitHub Pages (étape par étape)

### 1. Créer un compte GitHub
Si vous n'en avez pas encore : [github.com/signup](https://github.com/signup)

### 2. Créer un nouveau dépôt
- Allez sur [github.com/new](https://github.com/new)
- **Repository name** : `mypet360` (ou `mypet360-website`)
- Visibilité : **Public** ✅ (requis pour GitHub Pages gratuit)
- Cochez **"Add a README file"**
- Cliquez **"Create repository"**

### 3. Uploader les fichiers
- Dans votre dépôt, cliquez **"Add file" → "Upload files"**
- Glissez-déposez **tous les fichiers** de ce dossier (`index.html`, `README.md`)
- Message de commit : `Initial deploy - MyPet360 website`
- Cliquez **"Commit changes"**

### 4. Activer GitHub Pages
- Allez dans **Settings** (onglet en haut du dépôt)
- Dans le menu gauche : **Pages**
- Sous **"Source"** : sélectionnez **"Deploy from a branch"**
- Branch : **`main`** · Dossier : **`/ (root)`**
- Cliquez **"Save"**

### 5. Votre site est en ligne ! 🎉
Après 1 à 2 minutes, votre URL sera :
```
https://VOTRE-USERNAME.github.io/mypet360/
```
Exemple : `https://mypet360benin.github.io/mypet360/`

---

## 📁 Structure du projet

```
mypet360/
├── index.html        ← Application complète (SPA)
└── README.md         ← Ce fichier
```

Le site est un **Single Page Application (SPA)** — tout le code est dans `index.html`.  
Aucune dépendance externe (sauf Google Fonts via CDN).  
Fonctionne hors-ligne après le premier chargement.

---

## 🌐 Nom de domaine personnalisé (optionnel)

Pour utiliser `www.mypet360.bj` à la place de l'URL GitHub :

1. Achetez votre domaine auprès d'un registrar (ex: Gandi, Namecheap, OVH)
2. Dans GitHub Pages → **Custom domain** : entrez votre domaine
3. Chez votre registrar, ajoutez ces enregistrements DNS :
   ```
   CNAME  www   VOTRE-USERNAME.github.io
   ```
4. Cochez **"Enforce HTTPS"** dans GitHub Pages

---

## ✨ Pages & fonctionnalités

| Page | Description |
|------|-------------|
| 🏠 Accueil | Hero animé, stats, services, vétérinaires, témoignages |
| 🩺 Vétérinaires | 6 profils, filtres par spécialité, réservation |
| 🛍️ Boutique | 8 produits, sidebar catégories, panier complet |
| 🦮 Dog Walking & Garde | Promeneurs, 4 formules de garde, calculateur de prix |

### Fonctionnalités interactives
- ✅ Panier avec quantités modifiables et checkout
- ✅ Modal de réservation avec validation et écran de succès
- ✅ Calculateur de prix garde (dates → total automatique)
- ✅ Filtres vétérinaires et catégories boutique
- ✅ Sélecteur de paiement Mobile Money (MTN · Moov · Orange)
- ✅ Animations au scroll et micro-interactions
- ✅ Responsive mobile complet

---

## 🛠️ Modifications courantes

### Changer les prix
Ouvrez `index.html` et recherchez (`Ctrl+F`) : `FCFA`  
Modifiez les valeurs directement dans le HTML.

### Changer les informations de contact
Recherchez `WhatsApp` pour trouver les liens de contact.

### Ajouter un vétérinaire
Copiez un bloc `.vpc` existant dans la section `page-vets` et modifiez le contenu.

### Changer les couleurs
En haut du fichier, dans `:root { }`, modifiez les variables CSS :
```css
--gold: #C9933A;      /* Couleur or principale */
--forest: #1A3324;    /* Vert foncé */
--pine: #2D5C3F;      /* Vert moyen */
```

---

## 📞 Contact & Support

**MyPet360 Bénin**  
📍 Cotonou, Bénin  
💬 WhatsApp : +229 XX XX XX XX  
📧 contact@mypet360.bj

---

*Construit avec ❤️ pour le marché béninois.*
