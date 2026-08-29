Ce programme est un premier projet de **Pricer d'options** pour moi. Ce code n'est pas parfait mais présente une **manière de concevoir intéressante**.



Vous pouvez compiler ce programme simplement comme ceci mais assurez vous d'avoir **gcc comme compilateur sur votre machine** :



g++ {chemin_du_fichier} -o monte\_carlo.exe





Et ensuite pour **executer** :



./monte\_carlo.exe





L'implémentation du multi-threading est une des principales caractéristiques de ce programme. Cela permet de meilleure performance. Un système de calcul de temps d'execution permet de mesurer justement ces performances. Ce programme ne marche que pour des options européennes (le calcul se fait seulement à maturité T). 


This program is a first project of **Option Pricer** for me. This code isn't perfect but presents an **interesting construction**. 

You can compile this program with this sentence in your terminal but verify that you have **gcc as compiler on your computer** :

g++ {path\_of\_file} -o monte\_carlo.exe

And then to **execute** :

./monte\_carlo.exe
