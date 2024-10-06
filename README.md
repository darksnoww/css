# Les principales propriétés CSS

## 1. Mise en page (layout)
- **`display`** : Définit le type de boîte d'un élément (block, inline, flex, grid, etc.).
- **`position`** : Positionne un élément (relative, absolute, fixed, sticky).
- **`top`, `right`, `bottom`, `left`** : Position d'un élément par rapport à ses parents.
- **`z-index`** : Ordre de superposition des éléments.
- **`float`** : Fait flotter un élément à gauche ou à droite.
- **`clear`** : Stoppe l'effet de "float".

## 2. Espacement (margin, padding, etc.)
- **`margin`** : Espace extérieur autour d'un élément.
- **`padding`** : Espace intérieur (entre le contenu et la bordure).
- **`border`** : Bordure autour d'un élément.
- **`width`** : Largeur d'un élément.
- **`height`** : Hauteur d'un élément.
- **`max-width`, `max-height`** : Limite la largeur/hauteur maximale.
- **`min-width`, `min-height`** : Fixe la largeur/hauteur minimale.

## 3. Couleurs et arrière-plans
- **`color`** : Couleur du texte.
- **`background-color`** : Couleur de fond.
- **`background-image`** : Image en arrière-plan.
- **`background-position`** : Position de l'image de fond.
- **`background-size`** : Taille de l'image de fond.
- **`opacity`** : Transparence (0 à 1).

## 4. Typographie (textes et polices)
- **`font-family`** : Police du texte.
- **`font-size`** : Taille du texte.
- **`font-weight`** : Épaisseur du texte (normal, bold, etc.).
- **`line-height`** : Espace entre les lignes.
- **`text-align`** : Alignement du texte (gauche, centre, droite).
- **`text-decoration`** : Soulignement, surlignage, barré (underline, overline, line-through).
- **`text-transform`** : Change la casse du texte (uppercase, lowercase, capitalize).
- **`letter-spacing`** : Espacement entre les lettres.
- **`word-spacing`** : Espacement entre les mots.

## 5. Bordures, ombres et arrondis
- **`border`** : Crée une bordure autour d'un élément (taille, style, couleur).
- **`border-radius`** : Arrondit les coins.
- **`box-shadow`** : Ajoute une ombre autour d'un élément.

## 6. Flexbox (disposition flexible)
- **`display: flex`** : Active la disposition flexible.
- **`flex-direction`** : Orientation des éléments (row, column).
- **`justify-content`** : Aligne les éléments sur l'axe principal (start, center, space-between).
- **`align-items`** : Aligne sur l'axe secondaire (start, center, stretch).
- **`flex-wrap`** : Permet aux éléments de passer sur plusieurs lignes.

## 7. Grid (grille)
- **`display: grid`** : Active la disposition en grille.
- **`grid-template-columns`** : Définit les colonnes de la grille.
- **`grid-template-rows`** : Définit les lignes de la grille.
- **`gap`** : Espace entre les lignes et colonnes.
- **`grid-column`** : Positionnement ou taille des colonnes d'un élément.
- **`grid-row`** : Positionnement ou taille des lignes d'un élément.

## 8. Transitions et animations
- **`transition`** : Crée une transition fluide entre deux états.
- **`animation`** : Définit une animation en plusieurs étapes.
- **`transform`** : Applique des transformations comme la rotation, mise à l'échelle, déplacement (translate).
- **`@keyframes`** : Définit les étapes clés d'une animation.

## 9. Autres propriétés utiles
- **`overflow`** : Gère le débordement de contenu (visible, hidden, scroll, auto).
- **`visibility`** : Cache ou affiche un élément (visible, hidden).
- **`cursor`** : Change l'apparence du curseur (pointer, default, etc.).

## 10. Media queries (responsive design)
- **`@media`** : Change les styles selon la taille de l'écran (min-width, max-width).

## Exemple simple d'utilisation :
```css
/* Exemple d'une boîte flexible avec du texte centré */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f0f0f0;
}

.text {
  font-size: 24px;
  color: #333;
}
