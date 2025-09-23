# Anaylse de caractères
Créer un programme qui affiche la descriptoinn d'un caractère stocké dans une variable nomée `char_to_test`. Le programme doit afficher si le caractère est une lettre majuscule, une lettre minuscule, un chiffre, ou un caractère spécial (ni lettre ni chiffre).

## Exemple d'affichage
Si `char_to_test` vaut `'A'`, le programme doit afficher :
```Le caractère 'A' est une lettre majuscule.
```
Si `char_to_test` vaut `'g'`, le programme doit afficher :
```Le caractère 'g' est une lettre minuscule.
```
Si `char_to_test` vaut `'5'`, le programme doit afficher :
```Le caractère '5' est un chiffre.
```
Si `char_to_test` vaut `'@'`, le programme doit afficher :
```Le caractère '@' est un caractère spécial.
```

## Contraintes
- Utiliser des conditions `if`, `else if`, et `else` pour déterminer le type de caractère.
- Vous ne devez pas utiliser de fonctions de bibliothèque pour cette analyse (comme `isalpha`, `isdigit`, etc.). Utilisez les valeurs ASCII pour les comparaisons.