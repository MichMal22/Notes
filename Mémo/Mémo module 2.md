
>[!note] En Python, comme dans les autres langages, on utilise des **variables** pour **mémoriser des informations durant l'exécution d'un programme**.

>[!note] Pour mémoriser une information dans une variable, on utilise l'écriture suivante.

``variable = contenu

>[!note] Les informations numériques utilisent le point comme séparateur décimal.

>[!example] Par exemple un million : 1.000.000

>[!note] Les chaînes de caractères doivent être entourées de simples ou doubles guillemets.

>[!example] "chaîne de caractère" ou 'chaîne de caractère'

>[!note] Les valeurs logiques ne peuvent avoir qu'une des deux valeurs suivantes : True ou False.

>[!note] Les noms de variables doivent obligatoirement commencer par une lettre ou un souligné ; ne peuvent pas contenir d'espace ; peuvent contenir des lettres, des chiffres, des soulignés.

>[!done] Exemples de noms de variables **corrects** :
boite contenu total conteneur123_temperature

>[!fail] Exemples de nom de variables **incorrects** :
42reponse # affichage variable.123

>[!note] Les noms de variables sont sensibles à la casse.

>[!example] Par exemple : *variable1* et *VARIABLE1* sont **deux variables distinctes**

>[!note] Les noms de variables **ne peuvent pas être l'un de ces mots réservés** : and, del, for, is, raise, assert, elif, form, lambda, return, break, else, global, not, try, class, except, if, or, while, continue, exec, import, pass, yield, def, finally, in, print, as, with.

>[!note] L'**affichage du contenu d'une variable** peut se faire au moyen de la fonction **print**().

>[!example] Par exemple : print(variable)

>[!note] Une variable peut contenir le résultat d'une opération mathématique incluant d'autres variables ou pas.

>[!example] Exemple : total = prix * 1.21

>[!note] L'évaluation des expressions mathématiques est réalisée selon un ordre établi : d'abord ce qui se trouve entre parenthèses, ensuite les exposants, puis les multiplication et les divisions et, enfin, les additions et les soustractions.  
Le moyen mémotechnique pour se souvenir de cet ordre est **PEMDAS**.

>[!note] On peut **assembler deux chaînes de caractères** au moyen de l'opérateur +.  
Cette opération s'appelle **la concaténation**.

>[!example] Exemple : nom_complet = prenom + nom

>[!note] On peut **connaître le type d'une information contenu dans une variable** au moyen de la fonction **type**().

>[!example] Exemple : print( type (ma_variable))

>[!note] On peut **modifier le type d'une information** en utilisant une fonction de casting : **int**() pour transformer le contenu en entier, **float**() pour transformer l'information en nombre décimal, **str**() pour transformer une donnée en chaîne de caractères.

>[!example] Exemple : total = int ("1999.99)

>[!note] On peut **saisir une information à l'écran** au moyen de la fonction **input**().

>[!example] Par exemple : input ("Encodez votre prénom :")

