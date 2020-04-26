# Recettes
Lien: https://petitetambouille.github.io/recettes/index.html

Pour ajouter une recette, 
1. Aller dans la page appropriée
2. Compléter le bout de code
3. Ajouter entre des recettes dans la page appropriée
4. Ajouter un lien dans le menu sur la page principale

## Trouver la page appropriée
* Entree.html
* Plat.html
* Desserts.html

## Compléter le bout de code
Puis ajoutée la recette au format suivant en remplacant les mots en gras

* id représente un mot de clés unique, sans epsace, par exemple Boeuf Bourguignon, son id est "Boeuf_Bourguignon"
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

## Ajouter un lien dans le menu sur la page principale

Entrées, Plats et desserts représentent chacun un bloc.
Une fois que la recette a été crée, il suffit d'ajouter une ligne de code
* Mot clé sans espace est le ID que vous avez ajouté précédemment, il suffit de le collé ici

                    <li><a href="Plat.html#MOT CLE SANS ESPACE">NOM DE LA RECETTE</a></li>
                
