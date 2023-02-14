## Objetivo:
The password for the next level is stored in a file called **readme** located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game. 

## Datos de acceso al nivel:
- **Host: bandit.labs.overthewire.org** 
-  **Port:** 2220
- **User:** bandit0 
- **Password:** bandit0

## Solución:

``` bash
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
bandit0@bandit:~$
```

## Notas adicionales:
- El comando **ls** se utiliza para listar archivos o directorios en Linux y otros sistemas operativos basados en Unix.
- El comando de Linux **cat** concatena archivos y los muestra en el salida estándar.

## Referencias:
- [ls](https://man7.org/linux/man-pages/man1/ls.1.html) , [cd](https://man7.org/linux/man-pages/man1/cd.1p.html) , [cat](https://man7.org/linux/man-pages/man1/cat.1.html) , [file](https://man7.org/linux/man-pages/man1/file.1.html) , [du](https://man7.org/linux/man-pages/man1/du.1.html) , [find](https://man7.org/linux/man-pages/man1/find.1.html)