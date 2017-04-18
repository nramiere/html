# Blockchain

## Hash et Block
  
Un hash est une suite de caractères choisi en fonction d'un algorythme
et qui se base sur un block (un premier chiffre définissant ce block dasn une blockchain, voir plus bas), un nombre et des
données (datas). 

Le hash peut être défini comme la "carte d'identité" de la donnée
qu'on entre dans le block.

Peut importe la quantité de données, que ce soit une
lettre ou un livre entier, en fonction du format du hash choisi, 
le nombre de caractères sera toujours le même. L'absence de données 
elle-même peut être considérée comme une information: à une absence de datas
correspond un hash
  
## Blockchains et méthode de protection
 
Un block, bien souvent, se situe dans une blockchain, c'est-à-dire
litteralement une chaîne de blocks. Dans cette fameuse blockchain, tous
les blocks sont interdépendant. Le premier block seul est en quelque sorte
indépendant. Ainsi, le premier hash va permettre, en l'integrant dans l'algorythme
de créer le deuxième hash de le blockchain. Et ainsi de suite, sur des chaînes de parfois
4000 blocks !

La plupart des blockchains auront un code, un caractère dans leurs ash qui se répète.
On peut prendre pour exemple un hash qui commencerait par quatre 0.
 En rajoutant, ou en changeant les données d'un block, mettons celui du deuxième,
 le hash du block numero 2 va changer, entraînant une réaction en chaîne
 qui va donc changer le hash des blocks apres le 2, puisque leurs hash dépend de celui du 2.
 Afin de "récuperer" notre code, qui rappelons le, équivaut a quatre 0 a la fin du hash,
 on peut effectuer l'opération "remine" qui calcule le hash correspondant a la fois
 au code et a la fois aux données entrées. On recupère un hash qui nous convient dans cette blockchain, et seul
 notre numero a changé. Afin de récuperer un hash pour chaque block qui a changé, on effectue la même opération.
 
Bien qu'on ait vue qu'il soit plutôt compliqué de récuperer des codes qui correspondent avec 
notre base dans une blockchain puisque qu'il faut utiliser "remine" pour chaque block après avoir changé une donnée,
on peu imaginer qu'avec un ordinateur suffisant, il est possible de "reminer" tous les blocks dans une blockchain qui en contient
plusieurs milliers. Afin d'éviter ce risque, plusieurs copies des block
