# Application de calcul de l'âge

## Création des fichiers
je créé un fichier index.php qui va contenir un formulaire et un fichier traitement.php

## Le calcul
Je commence par ouvrir la balise php et créer une variable qui va contenir la date actuelle, je l'appelle ```$current_date```, je lui affecte la valeur  2020 pour le moment avec le type number.
Je créé une deuxième variable ```$birth_date```, je lui affecte l'année de ma naissance.
Je créé une 3e variable ```$age```, je lui affecte la soustraction des variables ```$current_date```et ```$birth_date```.
je fais un ```echo``` de la variable ```$age```.
```
<?php
$current_date = 2020;
$birth_date = 1985;
$age = $current_date - $birth_date;
echo "j'ai $age ans";
?>
```
