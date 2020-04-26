# Recettes
Lien: https://petitetambouille.github.io/recettes/index.html

**Attention, ne pas toucher le dossier nommé "CSS"**

Pour ajouter une recette c'est **SUPER FACILE, à condition de maitriser le copier/collé**
1. Aller dans la page appropriée
2. Compléter le bout de code & Ajouter entre des recettes dans la page appropriée
3. Ajouter un lien dans le menu sur la page principale

## 1.Trouver la page appropriée
* Entree.html
* Plat.html
* Desserts.html

## 2.Compléter le bout de code
Puis ajoutée la recette au format suivant en remplacant les mots en gras

* id représente un mot de clés unique, sans epsace, par exemple Boeuf Bourguignon, son id est "Boeuf_Bourguignon" **le mot clé doit être SANS ESPACE, le copié pour l'insérer dans l'index dans la suite tel qu'expliqué dans la 4ème partie**
* Nom de la recette est le nom tel qu'il va apparaitre en titre de recette
* Ingredients pour avoir une liste d'ingredients, si jamais vous avez besoin de plus d'ingrédients il suffit de copier la ligne et la recoller juste en dessous avant `</ul></h3>` 
* Texte pour avoir la recette séparée en plusieurs parties (saut à la ligne), si jamais vous avez besoin de plus de texte il suffit de copier la ligne et la recoller juste en dessous avant `</div>`


                <div class="skill-block" id="MOT CLE SANS ESPACE">
                 <h2 >NOM DE LA RECETTE</h2>
                  <h3 ><ul>
                    <li>INGREDIENT 1</li>
                    <li>INGREDIENT 2</li>
                    <li>INGREDIENT 3</li>
                  </ul></h3>
                  <h4>TEXTE 1</h4>
                  <h4>TEXTE 2</h4>                  
                  <h4>TEXTE 3</h4>
                  <h4>TEXTE 4</h4>
                </div>


Petite exception si la recette provient d'un site internet et que vous souhaitez y ajouter le site

                <div class="skill-block" id="MOT CLE SANS ESPACE">
                <h2 >NOM DE LA RECETTE</h2><a href="www.site.com">Recette originale ici</a>
                  <h3 ><ul>
                    <li>INGREDIENT 1</li>
                    <li>INGREDIENT 2</li>
                    <li>INGREDIENT 3</li>
                  </ul></h3>
                  <h4>TEXTE 1</h4>
                  <h4>TEXTE 2</h4>                  
                  <h4>TEXTE 3</h4>
                  <h4>TEXTE 4</h4>
                </div>
**WAOU! Bravo tu as fait tes premières lignes de code! Le plus dur a été fait!**

## Ajouter entre des recettes dans la page appropriée

Les recettes sont par ordre alphabétiques sur chaque page, chaque bloc de recette est séparé par un saut à la ligne. Le bloc de recette doit etre mis en dessous de:


      <!DOCTYPE html>
      <html>
        <head>
          <title>Recettes familiales
          </title>
          <meta name = "description" content="Recettes'">
          <meta charset = utf-8>
          <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
          <link rel="stylesheet" href="css/style.css">
        </head>

      <body>

          <div class="banner-index-entrees">
          <div class="container">
            <h1>Entrées</h1>
          </div>
          </div>

        <div class="card-sidebar navbar-icons">
          <ul>
            <li><a href="index.html">Recettes</a></li>
            <li><a href="Entree.html">Entrées</a></li>
            <li><a href="Plat.html">Plats</a></li>
            <li><a href="Dessert.html">Desserts</a></li>
          </ul>
        </div>

       <div class="container">
              <div class="skills-list" >
              
Et au dessus de

              </div>


         </div>

       </body>

      </html>
      
**Génial! T'es presque au bout, plus que l'index à mettre à jour!**

## 4.Ajouter un lien dans le menu sur la page principale

Entrées, Plats et desserts représentent chacun un bloc.
Une fois que la recette a été crée, il suffit d'ajouter une ligne de code
* Mot clé sans espace est le ID que vous avez ajouté précédemment, il suffit de le collé ici **cela doit être le même mot clé/id que sur la page de recette**

                    <li><a href="Plat.html#MOT CLE SANS ESPACE">NOM DE LA RECETTE</a></li>
                    
**Félicitations !**
                
