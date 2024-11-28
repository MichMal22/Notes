
>[!note]
>Un **commentaire** doit être précédé du symbole #. Tout ce qui suit ce symbole, sur la même ligne, sera ignoré par l'interpréteur Python.

>[!example]
>Par exemple ce code où "# si la personne est majeure..." et "# sinon..." n'ont rien à voir avec le script en lui-même, si ce n'est des **commentaires**. 
```
#!/bin/python3

age = input('Encodez votre âge :')
if int(age) >= 18:                       # si la personne est majeure...
  print('Bienvenue !')
else:                                    # sinon...
  print('Continue à manger ta soupe !')
```

>[!note]
>En Python, les conditions s'écrivent au moyen des instructions **if**, **else** et **elif**.

>[!note]
>Les opérateurs de comparaison sont : **==** (égalité), **!=** (inégalité), **>** (supériorité), **<** (infériorité), **>=** (supériorité ou égalité), **<=** (infériorité ou égalité).

>[!note]
>Le code qui doit être exécuté quand une condition logique est remplie doit être **indenté**.

>[!tip]
>**Indenter** ; Définition : (Typographie) **Mettre un alinéa, mettre un texte en retrait pour en faciliter la lisibilité**.

>[!example]
>Exemple :
```
if prenom == "Laurent":
    print("Bonjour Laurent")
```

>[!note]
>Le code qui doit être exécuté quand une condition logique n'est pas remplie doit être **indenté après l'instruction else**.

>[!example]
>Exemple :
```
if prenom == "Laurent":
    print("Bonjour Laurent")
else:
    print("Bonjour qui que tu sois !")
```

>[!note]
>On peut écrire des conditions logiques plus complexes au moyen des opérateurs logique **and or not**.

>[!example]
>Exemple :
>
```
if prenom == "Michel" and nom = "Dupont":
    print("Bonjour Michel Dupont")
```


>[!note]
>L'instruction **elif** fusionne un else et un if.

>[!example]
>Exemple :
```
if prenom == "Laurent":
    print("Bonjour Laurent")
elif prenom == "Patricia":
    print("Bonjour Patricia")
```

