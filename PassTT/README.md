#  Système d'Exploitation Un\*x, Langage C & Arduino

## Cours
* [Introduction aux réseaux](https://github.com/truillet/UT/blob/main/PassTT/Cours/introduction_reseaux.pdf) (2024)
* [Introduction à Arduino](https://github.com/truillet/UT/blob/main/PassTT/Cours/introduction_arduino.pdf) (2024)
* [Introduction aux Structures de données en C](https://github.com/truillet/UT/blob/main/PassTT/Cours/introduction_SdD.pdf) (2024)
  * [Types avancés en langage C](https://github.com/truillet/UT/blob/main/PassTT/Cours/types_avances_C.pdf)

## Travaux Pratiques
* **TP 1** : [Introduction à Arduino](https://github.com/truillet/UT/blob/main/PassTT/TP/TP1_Arduino.pdf) (2024)
  * **Code** : [capteur de distance](https://github.com/truillet/UT/blob/main/PassTT/Code/ultrason.zip)
  
<!-- * **TP 1** : [prise en main](https://github.com/truillet/UT/blob/main/PassTT/TP/TP1_Prise_en_main.pdf) (2023)
* **TP 2** : [premiers pas](https://github.com/truillet/UT/blob/main/PassTT/TP/TP2_Premiers_pas.pdf) (2023)
* **TP 3** : [première fonction](https://github.com/truillet/UT/blob/main/PassTT/TP/TP3_Premiere_fonction.pdf) (2023)
* **TP 4** : [Bibliothèque de fonctions](https://github.com/truillet/UT/blob/main/PassTT/TP/TP4_Bibliotheque.pdf) (2023)
* **Devoir Maison** : [Quaternions](https://github.com/truillet/UT/blob/main/PassTT/TP/DM_2023.pdf) (2023)
-->

## Quelques liens
* Commandes [Unix](https://en.wikipedia.org/wiki/List_of_Unix_commands)
* D. Ritchie, [The Development of the C Language](https://dl.acm.org/doi/10.1145/155360.155580), ACM SIGPLAN Notices, Volume 28, n° 3, March 1993, pp. 201-208
* [Quick and Dirty Guide to C](https://courses.cs.washington.edu/courses/cse351/14sp/sections/1/Cheatsheet-c.pdf)
* [Pointer Cheat Sheet](https://c-for-dummies.com/caio/pointer-cheatsheet.php)
* [Installer le sous-sytème ubuntu sous windows](https://learn.microsoft.com/fr-fr/windows/wsl/install)
* [Serveur X et WSL2 sous windows 10](https://medium.com/javarevisited/using-wsl-2-with-x-server-linux-on-windows-a372263533c3)
* [Utiliser VSCode avec WSL2](https://code.visualstudio.com/blogs/2019/09/03/wsl2)

```
# sous WSL 2 et windows 11, un serveur X est installé [Magic] ! 
# sous WSL 2 et windows 10, lancer d'abord un serveur X comme VcXsrv
# (N'oubliez pas de cliquer sur l'option "Disable access control")
# définir les variables d'environnement DISPLAY et LIBGL_ALWAYS_INDIRECT (à mettre dans le fichier .bashrc)
export DISPLAY=$(awk '/nameserver / {print $2; exit}' /etc/resolv.conf 2>/dev/null):0
export LIBGL_ALWAYS_INDIRECT=1
```
* [cheat.sh](https://cheat.sh)


