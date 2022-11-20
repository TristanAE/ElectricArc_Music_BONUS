# ElectricArc_Music_BONUS
Activer un arc électrique sur le rythme d’une musique

# I-	Conception électronique 

Pour concevoir le projet, j’utilise :

•	Un boitier de piles 5V

•	Un mini générateur haute tension

•	Un capteur sonore

•	Un relai

•	Un Arduino nano

Lorsqu’un téléphone joue de la musique proche du capteur sonore, celui-ci envoie 1 ou 0 en fonction des impulsions vers l’Arduino. En fonction de la réponse reçue, le relai doit s’ouvrir ou se fermer.

On connecte l’Arduino aux pins D2, VCC et GND du relai ainsi que le capteur sonore aux pins D3, VCC et GND.

La borne positive du boitier de pile est branchée au relai dans le compartiment NO et la borne positive du générateur haute tension dans celui noté COM. On soude ensuite les deux pôles négatifs de la pile et du générateur ensemble. Le circuit est fermé.

A chaque forte tonalité du son de la musique, l’Arduino ouvre le relai et laisse le courant de la pile se propager dans le générateur haute tension, ce qui active un arc électrique. 

# II-	Conception informatique et modélisation 

Le programme de l’Arduino consiste simplement à lire la valeur retournée par le capteur sonore et en fonction, ouvrir ou fermer le relai.
On modélise une structure pour placer le générateur haute tension à l’intérieur et on peut également souder deux tiges métalliques à l’extrémité de ses deux fils.

![Picture1](https://user-images.githubusercontent.com/92324336/202909465-5457011e-91f6-4e5e-86cc-158f8df5f7de.png)

# III-	Rendu final 

Musique utilisée : Future-Mask off

Gif peu intéressant sans le son…
 
 ![ezgif com-gif-maker (8)](https://user-images.githubusercontent.com/92324336/202909437-9460574b-69c8-4683-a42c-949de116bfe3.gif)


 
