# ⚡ PokéVault - Ultimate Collector Experience

> Une application web moderne, ultra-fluide et élégante conçue pour les collectionneurs de cartes Pokémon. Gérez vos **Chase Cards** (cartes recherchées), votre collection de cartes possédées, suivez la valeur de votre investissement et organisez vos propres pages personnalisées.

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-%2338BDF8.svg?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TCGdex API](https://img.shields.io/badge/API-TCGdex-purple)

---

## ✨ Fonctionnalités Clés

* **Recherche Intelligente connectée à TCGdex API :** Parcourez les extensions officielles (triées de la plus récente à la plus ancienne) et filtrez par Pokémon pour récupérer instantanément les visuels officiels et les informations de cartes.
* **Double Mode de Gestion (Wishlist & Collection) :** 
  * 🎯 **Chase Cards :** Suivez les cartes que vous recherchez activement avec leur cote Cardmarket estimée.
  * 📦 **Cartes Possédées :** Suivez vos cartes obtenues, qu'elles proviennent d'un ouverture de booster (*Pull* à 0 €) ou d'un achat à l'unité (*Single*).
* **Dashboard Analytique en Temps Réel :** Visualisez instantanément le total investi, la valeur totale de votre collection sur le marché, les plus-values nettes et vos taux de rentabilité (ROI) ou de complétion.
* **Pages Personnalisées sur-mesure :** Créez vos propres thèmes ou *Master Sets* (ex: *Master Set 151*, *Évolutions Prismatiques*), associez-y vos cartes et réorganisez l'ordre des pages à l'aide des flèches de gestion.
* **Effets & Immersion :** Effet holographique interactif au survol des cartes, modale de zoom haute résolution, animations de célébration (confettis + sons dynamiques) lorsque vous marquez une carte comme obtenue.
* **100% Autonome & Sauvegarde Locale :** Aucune base de données complexe requise. Tout est stocké en local (`localStorage`) sur votre navigateur avec une fonction d'export et d'import de sauvegarde au format JSON.

---

## 🚀 Utiliser le projet

Étant donné que l'application est entièrement contenue dans un seul fichier `index.html` (avec Tailwind CSS, FontAwesome et les scripts embarqués), elle ne nécessite **aucun serveur Node.js ni installation complexe**.

### Option 1 : Utilisation locale
1. Téléchargez ou clonez ce dépôt sur votre machine.
2. Double-cliquez simplement sur le fichier `index.html` pour l'ouvrir dans votre navigateur web favori.

### Option 2 : Publication sur GitHub Pages (Recommandé)
Vous pouvez publier ce fichier directement en ligne gratuitement en quelques clics :
1. Déposez votre fichier `index.html` à la racine de votre dépôt GitHub.
2. Rendez-vous dans les **Settings** (Paramètres) de votre dépôt sur GitHub.
3. Allez dans l'onglet **Pages** (dans le menu latéral gauche).
4. Sous *Build and deployment*, dans la section **Branch**, sélectionnez `main` (ou `master`) et `/ (root)`, puis cliquez sur **Save**.
5. Votre application sera en ligne en quelques secondes à l'adresse indiquée par GitHub !

---

## 🛠️ Stack Technique

* **Structure & Style :** HTML5, [Tailwind CSS](https://tailwindcss.com/) (via CDN).
* **Icônes & Typographie :** [FontAwesome](https://fontawesome.com/) & [Google Fonts (Plus Jakarta Sans)](https://fonts.google.com/).
* **Données Pokémon :** [TCGdex API](https://tcgdex.net/) pour la récupération des séries et des visuels.
* **Effets visuels :** [Canvas Confetti](https://www.npmjs.com/package/canvas-confetti) pour les animations de réussite.

---

## 📄 Licence

Ce projet est open-source et mis à disposition sous licence MIT. N'hésitez pas à l'utiliser, le modifier ou l'adapter pour vos propres collections !
