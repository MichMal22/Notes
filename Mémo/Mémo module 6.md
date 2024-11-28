
>[!note]
>Une chaîne de caractères est **délimitée par des guillemets**.

>[!example]
```
ville = "Charleroi"
```

>[!note]
>L'**assemblage de deux chaînes de caractères** au moyen de l'opérateur plus s'appelle la *concaténation*.

>[!note]
>On peut **extraire une partie d'une chaîne de caractères** en ajoutant une information entre crochets du type
>\[ indice_premier_caractère:indice_caractere_qui_suit_le_dernier_a_prendre].

>[!example]
>Exemple :
```
ville = "Namur"
amu = ville \[1:4] 
```

>[!note]
>On peut **connaître le nombre de caractères d'une chaîne de caractères** au moyen de la fonction len().

>[!example]
>Exemple :
```
prenom = input("Encodez votre prénom :")
nb_caracteres = len(prenom)
print(prenom, "contient", nb_caracteres, "caractères")
```

>[!note]
>On peut **vérifier la présence d'une chaîne de caractères dans une autre chaîne de caractères** au moyen de l'intruction in.

>[!example]
>Exemple :
```
lettre = input("Encodez une lettre :")
if lettre in "catapulte":
	print("Il y'a un ou plusieurs", lettre, "dans le mot catapulte")
```

