
>[!note]
>Les liste sont des collections d'éléments qui **peuvent être de types différents.**

>[!note]
>On **délimite une liste au moyen de crochets** et en **séparant les éléments au moyen de virgules.**

>[!example]
>Exemple :
```
un_peu_de_tout = ["pomme",3.1415,True,10]
```

>[!note]
>On accède à un élément d'une liste en utilisant l'indice de cet élément entre crochet.

>[!example]
>Exemple :
```
encore_de_tout = [1999,"Bruxelles",19.99]
deuxieme_element = encore_de_tout[1]
```

>[!note]
>Dans une liste, les éléments sont indicés **à partir de 0**.

>[!note]
>La fonction **len() permet de retourner le nombre d'éléments** contenus dans une liste.

>[!note]
>Pour **ajouter un élément à une liste**, on utilise la fonction append() de la manière suivante :
```
maListe = ["Lundi","Mardi,","Mercredi","Jeudi"]
maListe.append("Vendredi")
```

>[!note]
>On peut **rechercher la présence d'un élément dans une liste** au moyen de l'instruction in.

>[!example]
>Exemple :
```
suspects = ["Toi","Vous","Moi"]
if "Moi" in suspects:
    print("Zut ! Je suis découvert !"))
```

>[!note]
>On peut **trier une liste** au moyen de la fonction sort().

