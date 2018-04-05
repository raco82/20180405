# 20180405

A voir sur : 

https://cdn.rawgit.com/raco82/20180405/ec54e6a5/index.html



Pimper la page Google avec du JavaScript

Tu vas reprendre le projet d'hier et ajouter un peu de JavaScript pour le rendre un peu mieux.
0. Mise en place

Pour ce projet, nous allons te demander de reprendre le projet de la veille, mais de le faire sur un nouveau repository Github. Ce sera plus pratique pour les corrections.
1. Warmup

Reprends la page Google de la veille. Fais en sorte que quand tu arrives sur la page, les éléments centraux (logo, barre de recherche, boutons) ne sont pas encore affichés. À la place, il y aura un gros bouton "AFFICHER LES ÉLÉMENTS CENTRAUX". Quand tu cliques sur ce bouton, le bouton va disparaître, et les éléments centraux (logo, barre de recherche, boutons) vont apparaître.
2. Redirection

Maintenant on va faire marcher la recherche de Google. Quand tu fais une recherche, et clique sur le bouton "Recherche Google", la page dois te rediriger vers la recherche correspondante. Par exemple si tu tappes hello world et clique sur "Recherche Google", cela doit te rediriger sur https://www.google.fr/#q=hello+world. Si tu tappes bonjour monde, tu iras sur https://www.google.fr/#q=bonjour+monde
3. Popup

Ton site est trop bien, mais une grande entreprise de vidéos pornographiques te propose un contrat que tu ne peux pas refuser : contre 250 milliards de dollars zimbabwéen, tu dois afficher une popup en plein milieu de la page qui affiche "Hey le site xxxvidsxxx est trop bien. Viens dessus stp please" au bout de 10 secondes sur le site. La popup peut être en alert(). Pour ceux qui sont chauds, vous pouvez utiliser une popup un peu plus moderne.
4. Générateur de grilles

Cet exercice est pour les champions : ne pas y arriver n'est pas grave 😉

Tu vas faire une autre page sur ton site : un générateur de grille. Une page web qui va demander à l'utilisateur la taille de la grille, et sortira une grille.

Faire une page toute nouvelle. Cette page va demander à l'utilisateur (via un alert) la taille de sa grille, un nombre de 1 à 70, que l'on appèlera N. Puis la page va afficher une carré qui contien N x N petits carrés égaux.

    Au début, fais des carrés qui ont une taille prédéterminée
    Maintenant, tous ces petits carrés doivent rentrer dans un grand carré qui rentre dans la page. Ainsi, si l'utilisateur répond qu'il veut une grille de 1 x 1, le petit carré aura la taille de width_grand_carré x heigth_grand_carré. S'il veut une grille de 3 x 3, les petits carrés auront une taille de (width_grand_carré / 3) x (heigth_grand_carré / 3), et ainsi de suite

(hint : la boucle for est ton amie)

