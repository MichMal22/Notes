
>[!note]
>En Python, la boucle "Tant que..." s'écrit au moyen de l'instruction **while**.

>[!example]
>Exemple :
```
reponse = "oui"
while reponse != "non":
    reponse = input("On continue ?")
```

>[!note]
>On peut forcer la sortie d'une boucle au moyen de l'instruction **break**

>[!note]
>On peut forcer le passage à l'itération suivante au moyen de l'instruction **continue.**

>[!note]
>L'instruction **range** permet de créer une liste de valeurs que l'on peut parcourir au moyen de l'instruction for.

>[!example]
>Exemple :
```
for prenom in ("Laurent", "Hicham", "Gésaelle"):
    print("Bonjour",prenom)
```

>[!note]
>En Python, la boucle "Pour...de ... à... par pas de ..." s'écrit au moyen de l'instruction **for**.

>[!example]
>Exemple :
```
for chiffre_impair in range(1,11, 2):
    print(chiffre_impair)
```
