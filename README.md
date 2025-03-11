# Ohmyfood 🍽️

Ohmyfood est un site web mobile-first qui permet aux utilisateurs de commander des menus gastronomiques de restaurants haut de gamme.
Pour l'instant, 4 menus de restaurants sont disponibles sur le site.

## 📌 Fonctionnalités
- Interface responsive (Mobile-First)
- Affichage de 4 menus de restaurants
- Animations et transitions CSS (sans JavaScript)

## 🚀 Technologies utilisées
- VS Code
- HTML
- SCSS (SASS via Node.js)
- Git/GitHub

## 📂 Structure du projet
📂 Ohmyfood/  
├── 📂 css/  
│   ├── 🎨 style.css  
│   ├── 🎨 style.css.map  
├── 📂 data/  
│   ├── 📄 Oh my food - Textes.txt  
├── 📂 images/  
│   ├── 📂 icons/  
│   │   ├── 🔣 arrow_back.svg  
│   │   ├── 🔣 format_list_bulleted.svg  
│   │   ├── 🔣 smartphone.svg  
│   │   ├── 🔣 storefront.svg  
│   ├── 📂 logo/  
│   │   ├── 🏷️ ohmyfood.png  
│   │   ├── 🏷️ ohmyfood@2x.svg  
│   ├── 📂 restaurants/  
│   │   ├── 🖼️ jay-wennington-N_Y88TWmGwA-unsplash.jpg  
│   │   ├── 🖼️ louis-hansel-shotsoflouis-qNBGVyOCY8Q-unsplash.jpg  
│   │   ├── 🖼️ stil-u2Lp8tXIcjw-unsplash.jpg  
│   │   ├── 🖼️ toa-heftiba-DQKerTsQwi0-unsplash.jpg  
├── 📂 menus/  
│   ├── 📜 menu1.html  
│   ├── 📜 menu2.html  
│   ├── 📜 menu3.html  
│   ├── 📜 menu4.html  
├── 📂 scss/  
│   ├── 🎭 _animations.scss       // Animations et transitions  
│   ├── 📝 _base.scss             // Styles de base (typographie, éléments généraux)  
│   ├── 🧩 _components.scss       // Composants réutilisables (boutons, cartes...)  
│   ├── 📐 _layout.scss           // Disposition générale (header, footer...)  
│   ├── 📱 _media.scss            // Media queries pour le responsive  
│   ├── 📄 _pages.scss            // Styles spécifiques aux pages (index, menus...)  
│   ├── 🎨 _variables.scss        // Variables globales (couleurs, polices...)  
│   ├── 🖌️ style.scss             // Fichier principal qui importe tout  
├── 🚫 .gitignore  
├── 🏠 index.html  
├── 📖 README.md



N.B : Les fichiers CSS sont créés par Node.js après la compilation des fichiers SCSS.

### 🛠️ Dernières modifications
- Finalisation de la partie Footer
- Création du lien entre la page index.html et menu1.html en cliquant sur les cartes
- Création & Finalisation de la page menu1.html
- Changements de l'image cœur pour les icônes de Font Awesome
- Création de l'animation pour le bouton "Like" (en cours)


### 🔮 À venir
- Animations pour le bouton "Like" et la carte de menu
- Création des pages menu2.html, menu3.html & menu4.html
- Media queries vers tablette & desktop