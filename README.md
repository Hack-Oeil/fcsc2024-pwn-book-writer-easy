# FCSC 2024 Book Writer (Easy)

La startup TypeWriters & Co. a une idée géniale : elle souhaite proposer en ligne un service de traitement de texte qui va révolutionner le monde de l’édition !

Mais la veille de l’inauguration, le chef de projet se souvient d’une vague mention concernant des exigences de sécurité…

Comme vous êtes la personne chargée de la sécurité, il a besoin de votre validation. Selon lui, cela n’est qu’une simple formalité car le code a été relu par leurs meilleurs développeurs et le binaire s’exécute avec toutes les protections classiques (canaris, W^X, ASLR, etc.).

Vérifiez s’il est possible de lire le fichier *flag.txt* qui se trouve sur le serveur distant.

Une variante plus difficile de cette épreuve est disponible : **Book Writer**.



Fichiers :
- [book-writer-easy](book-writer-easy) (Application)
- [book-writer-easy.c](book-writer-easy.c) (Code source)



Auteur : AMI

Origine : [Book Writer (Easy)](https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-book-writer-easy/)


-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc book-writer-easy.cyrhades.fr 4000

-----------

## Ou directement avec netcat
> nc localhost 4000

-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-pwn-book-writer-easy.git

> cd fcsc2024-pwn-book-writer-easy

-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-book-writer-easy/