#  Systèmes d'Exploitation Un\*x et Langage C

## Cours

## Quelques liens
* D. Ritchie, [The Development of the C Language](https://dl.acm.org/doi/10.1145/155360.155580), ACM SIGPLAN Notices, Volume 28, n° 3, March 1993, pp. 201-208
* [Quick and Dirty Guide to C](https://courses.cs.washington.edu/courses/cse351/14sp/sections/1/Cheatsheet-c.pdf)
* [Pointer Cheat Sheet](https://c-for-dummies.com/caio/pointer-cheatsheet.php)
* [Installer le sous-sytème ubuntu sous windows](https://learn.microsoft.com/fr-fr/windows/wsl/install)
* [Serveur X et WSL2](https://medium.com/javarevisited/using-wsl-2-with-x-server-linux-on-windows-a372263533c3)

```
# sous WSL 2 et windows 11, un serveur X est installé [Magic] ! 
# sous WSL 2 et windows 10, lancer d'abord un serveur X comme VcXsrv
# (N'oubliez pas de cliquer sur l'option "Disable access control")
# définir les variables d'environnement DISPLAY et LIBGL_ALWAYS_INDIRECT (à mettre dans le fichier .bashrc)
export DISPLAY=$(awk '/nameserver / {print $2; exit}' /etc/resolv.conf 2>/dev/null):0
export LIBGL_ALWAYS_INDIRECT=1
```

## Travaux Pratiques
* **TP 1** : [prise en main]() (2023)
