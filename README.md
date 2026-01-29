# Hôtel UP - Site Vitrine Luxe 5 Étoiles

Un site web élégant et professionnel pour l'Hôtel UP à Lille, conçu pour offrir une expérience premium et diriger les visiteurs vers la page de réservation Booking.com.

## 🌟 Caractéristiques

### Design Premium
- **Palette de couleurs luxueuse** : Or (#D4AF37), Noir profond (#1a1a1a), Beige crème (#F5F3ED)
- **Typographies Google Fonts** :
  - Playfair Display (serif élégant) pour les titres
  - Inter (sans-serif moderne) pour le corps de texte
- **Animations fluides** : Fade-in, slide-up, hover effects
- **Design responsive** : Optimisé pour mobile, tablette et desktop

### Pages

#### Page d'Accueil (`index.html`)
- Hero slider automatique avec 3 slides
- Section bienvenue avec texte raffiné
- Grid de 8 services premium avec icônes
- Galerie d'images interactive avec lightbox
- Call-to-action vers Booking.com
- Préloader élégant

#### Page Chambres (`rooms.html`)
- Présentation détaillée de 2 types de chambres
- Images générées par IA de haute qualité
- Listes complètes d'équipements
- Section salle de bain luxe
- CTA multiples vers Booking.com

#### Page Contact (`contact.html`)
- Cards d'informations de contact
- Carte Google Maps intégrée
- Formulaire de contact stylisé
- Liste détaillée des distances
- Informations pratiques (check-in/out, parking)

### Fonctionnalités JavaScript (`script.js`)
- ✅ Préloader au chargement
- ✅ Menu hamburger mobile responsive
- ✅ Smooth scroll pour navigation fluide
- ✅ Hero slider automatique (5s par slide)
- ✅ Animations au scroll (Intersection Observer)
- ✅ Lightbox pour galeries d'images
- ✅ Navbar avec effet au scroll
- ✅ Validation de formulaire
- ✅ Lazy loading d'images

### Assets Générés
Toutes les images principales ont été créées avec l'IA pour assurer un rendu cohérent et professionnel :
- `hotel_exterior_hero_*.png` - Façade extérieure luxueuse
- `chambre_double_deluxe_*.png` - Chambre double premium
- `chambre_twin_modern_*.png` - Chambre twin élégante
- `bathroom_luxury_*.png` - Salle de bain en marbre
- `lobby_reception_*.png` - Lobby et réception design

## 📂 Structure du Projet

```
hotel-boa-lille-main/
├── index.html          # Page d'accueil avec hero slider
├── rooms.html          # Page chambres détaillée
├── contact.html        # Page contact avec carte et formulaire
├── style.css           # Design system premium complet
├── script.js           # Interactions et animations
├── images/             # Images générées par IA
│   ├── hotel_exterior_hero_*.png
│   ├── chambre_double_deluxe_*.png
│   ├── chambre_twin_modern_*.png
│   ├── bathroom_luxury_*.png
│   └── lobby_reception_*.png
└── README.md           # Ce fichier
```

## 🚀 Utilisation

### Ouverture locale
1. Ouvrez `index.html` dans votre navigateur
2. Le site fonctionne en local sans serveur nécessaire

### Déploiement
Pour héberger le site en ligne :

#### Option 1 : GitHub Pages (Gratuit)
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin <votre-repo-github>
git push -u origin main
```
Activez GitHub Pages dans Settings → Pages → Source: main branch

#### Option 2 : Netlify Drop (Gratuit)
1. Allez sur https://app.netlify.com/drop
2. Glissez-déposez le dossier du projet
3. Votre site est en ligne immédiatement !

#### Option 3 : Serveur FTP traditionnel
Uploadez tous les fichiers via FileZilla ou votre client FTP préféré.

## 🎨 Personnalisation

### Modifier les couleurs
Dans `style.css`, ligne 6-16, modifiez les variables CSS :
```css
--accent-gold: #D4AF37;  /* Changer la couleur or */
--primary-dark: #1a1a1a; /* Changer le noir */
--bg-cream: #F5F3ED;     /* Changer le beige */
```

### Changer le lien Booking.com
Remplacez tous les liens contenant :
```
https://www.booking.com/hotel/fr/up.html?aid=2402550&label=hotel-des-reignaux.fr
```
Par votre propre lien affilié Booking.com

### Modifier les textes
Éditez directement les fichiers HTML pour changer :
- Titres et descriptions
- Noms des chambres
- Informations de contact
- Adresse et distances

### Remplacer les images
Placez vos propres images dans le dossier `images/` et mettez à jour les chemins dans les fichiers HTML.

## 📱 Responsive Design

Le site s'adapte automatiquement à toutes les tailles d'écran :
- **Desktop** : Layout complet avec grilles 2-3 colonnes
- **Tablette (< 1024px)** : Grilles optimisées 1-2 colonnes
- **Mobile (< 768px)** : Menu hamburger, grilles 1 colonne, textes ajustés

## 🌐 SEO

- Meta descriptions sur toutes les pages
- Balises meta keywords
- Structure HTML sémantique
- Alt texts sur toutes les images
- Liens internes optimisés

## 🎯 Optimisations

- **Performance** : Animations CSS3 optimisées (60fps)
- **Accessibilité** : Structure HTML sémantique
- **Compatibilité** : Chrome, Firefox, Safari, Edge (dernières versions)
- **Poids** : Site léger, chargement rapide

## 📞 Support

Pour toute modification ou question technique, consultez les commentaires dans le code.

## 📄 Licence

Site vitrine pour Hôtel UP Lille. Tous droits réservés © 2024.

---

**Développé avec ❤️ pour offrir une expérience digitale premium à l'image de votre hôtel 5 étoiles.**