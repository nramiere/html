# Blockchain

## Hash et Block
  
Un hash est une suite de caractères choisis en fonction d'un algorithme et qui se base sur un block, un nombre et des données (data). 
Le hash peut être défini comme la "carte d'identité" de la donnée qu'on entre dans le block.
Peut importe la quantité de données, que ce soit une lettre ou un livre entier, en fonction du format du hash choisi, le nombre de caractères sera toujours le même.
L'absence de données elle-même peut être considérée comme une information: à une absence de datas correspond un hash

  
## Blockchains et méthode de protection
 
Un block, bien souvent, se situe dans une blockchain, c'est-à-dire litteralement une chaîne de blocks.
Dans cette fameuse blockchain, tous les blocks sont interdépendant.
Le premier block seul est en quelque sorte indépendant.
Ainsi, le premier hash va permettre, en l'integrant dans l'algorithme de créer le deuxième hash de la blockchain.
Et ainsi de suite, sur des chaînes de parfois 4000 blocks !


La plupart des blockchains auront un code, un caractère dans leurs hash qui se répète.
On peut prendre pour exemple un hash qui commencerait par quatre 0.
En rajoutant, ou en changeant les données d'un block dans la chaîne, le hash du block numero 2 va changer, ce qui va entraîner les changement des hash des blocks après le 2.
Afin de "récuperer" notre code, on peut effectuer l'opération "remine" qui calcule le hash correspondant à la fois au code et à la fois aux données entrées. 
On recupère un hash qui nous convient dans cette blockchain, et seul notre numéro a changé. 
Afin de récuperer un hash pour chaque block qui a changé, on effectue la même opération.
L'obligation de "reminer" chaque block est déjà une bonne sécurité en soit, mais il y en a une autre, en plus.
Chaque blockchain a plusiuers copies d'elle-même;
Si quelqu'un change une donnée, et prend toutes ses précautions pour éviter que ça ce voit, il ne pourra pas retrouver le hash d'orgine.
Les copies mettent en évidence les differences de hash, et empechent les fraudes.

## Tokens et Coinbase

Ces blockchains sont très utiles dans les transactions financières.
L'affichage des transactions dans un block est appelé Token.
C'est un un passage d'argent d'une personne X à une personne Y.
Les blockchains permettent de suivre la progression de l'argent.
Les differents transactions corrrespondent a des hash.
Afin de voir d'où vient l'argent de la transaction, le hash du block précédent est affiché.
Puisque l'argent doit a la base être donné à quelqu'un pour commencer des transactions, on rajoute la coinbase.
C'est-à-dire que Monsieur X reçoit une somme  de $100 qui lui permettra de payer Madame Y.
 
La coinbase est affichée au dessus des données afin de rappeler d'où vient l'argent à la base.
 
## Conclusion

Les blockchains sont un moyen sûr d'assurer les transactions financières en toute sûreté.
La complexité des hash diffère en fonction de l'importance des données traitées.
L'algorithme de calcul des blockchains est en constante évolution, afin de rester efficace.
 
 




 
 

