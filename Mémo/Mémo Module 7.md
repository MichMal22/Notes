
>[!note]
>Pour **lire un fichier**, il faut l'ouvrir en lecture au moyen de la fonction open().

>[!example]
>Exemple :
```
fichier = open("nom_du_fichier","r")
```


>[!note]
>On peut **gérer les problèmes liés à l'ouverture d'un fichier** au moyen des instructions **try:** et **except:. else:

>[!example]
>Exemple : 
```
try:
    fichier = open("liste_livres.txt","r")
except:
    print("L'ouverture du fichier a échoué")
```


>[!note]
>Le caractère \\n ("new ligne") indique une **fin de ligne dans un fichier**.


>[!note]
>En cas de **difficultés de lecture à l'encodage des caractères** dans un fichier, on peut utiliser la fonction open du module codecs qui permet de spécifier le type d'encodage des caractères.

>[!example]
>Exemple :
```
import codecs
monfichier = codecs.open("journal.log","r","utf-8")
```

