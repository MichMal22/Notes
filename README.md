# Notes
Juste mes notes faites en autodidacte

# Naissance de Python

<strong>C'est un langage <em>interprété</em> créé en 1991 par un développeur néerlandais, Guido van Rossum.</strong>

``Il est particulièrement indiqué l'apprentissage de la programmation en raison de sa clarté, de sa syntaxe et de sa structure.

Ce langage est très intéressant parce qu'il est portable (fonctionne avec différentes systèmes d'exploitation) et peut servir dans de nombreux domaines informatiques.

>**Python peut être utilisé dans de nombreuses situations :

- Écriture de scripts système.
- Calculs scientifiques.
- Conception d'applications.
- Développement web.
- Analyse et traitement de données.

>[!info] La documentation officielle du langage Python est consultable (en anglais) à l'adresse  [**https://www.python.org/doc/**](https://www.python.org/doc/).

# Langages interprétés

**Les langages peuvent être classés selon leur mode de « traduction » (la façon dont on transforme le programme écrit par être humain en quelque chose de compréhensible par la machine).

Les deux principaux modes sont : ***l'interprétation*** et ***La compilation***.

``Un LANGAGE INTERPRÉTÉ est un langage qui nécessite un programme (un interpréteur) pour traduite (interpréter) ce qui est écrit dans le langage informatique en un langage compris par la machine (des 1 et des 0).

![[Pasted image 20240628163813.png]]
``Schéma décrivant l'interprétation d'un langage de programmation.

>[!info] En informatique les scripts sont des programmes.


# Langages compilés

**Face aux langages interprétés, il y'a les *langages compilés*.

Un compilateur transforme l'entièreté du code source d'un programme en un fichier exécutable. Cela permet de se passer d'un programme tiers (interpréteur par exemple) pour exécuter le programme.

![[Pasted image 20240628163636.png]]
``Schéma décrivant la compilation d'un langage de programmation.

# Comparaison interpréteur / compilateur

**Avantages d'un interpréteur**
	- Exécution instantanée appréciée des débutants
	- L'exécution requiert moins d'espace mémoire (RAM)
	- La modification du script est aisée
	- Le script peut être exécuté sous n'importe quel système d'exploitation pouvant exécuter l'interpréteur

**Inconvénients d'un interpréteur**
	- Exécution plus lente que la compilation
	- La présence de l'interpréteur est requise lors de chaque exécution

**Avantages d'un compilateur**
	- Plus rapide à l'exécution
	- Code source non visible des autres utilisateurs
	- Une fois compilé, le fichier est autonome pour son exécution

**Inconvénients d'un compilateur**
	- Re-compilation nécessaire à chaque modification du code source
	- L'exécution requiert plus d'espace mémoire (RAM)

# Python, compilé ou interprété ?

**Il est souvent écrit que Python est un langage interprété. C'est en fait un peu plus compliqué que cela.

Python utilise *interprétation et compilation* :

- 1. Le code source du script passe d'abords par une phase de compilation qui crée du *bytecode*.
- 2. Ensuite, le *bytecode* est interprété par une *machine virtuelle applicative*.

Mais ce n'est pas encore pour tout de suite, on verra ça plus tard.

>[!info] Le bytecode est un code intermédiaire entre les instructions machines et le code source. En informatique, une machine virtuelle (anglais virtual machine, abr. VM) est un programme qui crée une illusion d'un appareil informatique.

# L'interpréteur Python

**L'interpréteur du langage Python est téléchargeable sur le site officiel du langage à l'adresse [https://www.python.org/downloads/](https://www.python.org/downloads/).

# Les scripts Python

**Tout programme écrit en Python est appelé un script (c'est lié au concept d'interprétation).      
Le code Python qui n'est pas encore interprété est appelé *code source*.

**Quand l'on écrit du code Python et que l'on l'enregistre dans un fichier, on a écrit un script sous la forme de code source. Ce code source peut ensuite être interprété.

**Les fichiers contenant le code source de scripts Python doivent avoir *l'extension .py*.

![[Pasted image 20240628172156.png]] 
`` Icône d'un fichier contenant le code source d'un script Python.

Comme ici j'utilise (au moment où j'écris ici) un interpréteur en ligne (l' l'application trinket.io), il ne faudra pas enregistrer votre code source sur votre ordinateur.
Par défaut, le nom du script Python sur trinket.io sera main.py.
![[Pasted image 20240628173346.png]]
``Le nom du script dans l'interpréteur en ligne trinket.io



Cependant, **afin de rendre mon apprentissage plus « confortable »**, j'utilise un interpréteur intégré à la plateforme de cours : [https://trinket.io/](https://trinket.io/).

>[!todo] Donc il n'y a rien à télécharger :D

