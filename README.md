# Exercice Bootstrap 3 - Maquette Responsive

Intégrez la maquette en utilisant la grille Bootstrap. Faites en sorte qu'elle s'adapte à toutes les tailles d'écran représentés par les artboards.

☝️ Commencez par intégrer la grille, puis insérez le contenu par après.

Les éléments nécessaires à l'intégration se trouvent dans le dossier **\_consigne**.

Afin de rendre les colonnes visibles lors de la première étape, vous pouvez utiliser la CSS suivante:

```CSS
.row + .row {
  margin-top: 16px;
}

.row > .col,
.row > [class^=col-] {
  padding-top: 12px;
  padding-bottom: 12px;
  background-color: rgba(86, 61, 124, .15);
  border: 1px solid rgba(86, 61, 124, .2);
}
```

![](_consigne/maquette@1x.png)
