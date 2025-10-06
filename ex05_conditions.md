## Exercice 1 — if simple
Donner l'affichage exact du programme suivant :
```c
int a = 5;
if (a > 3) {
    printf("OK\\n");
}```

## Exercice 2 — if/else
Donner l'affichage exact du programme suivant :
```c
int x = 10;
if (x < 0) {
    printf("negatif\\n");
} else {
    printf("non-negatif\\n");
}
```

## Exercice 3 — if/else if/else
Donner l'affichage exact du programme suivant :
```c
int n = 7;
if (n == 0) {
    printf("zero\\n");
} else if (n % 2 == 0) {
    printf("pair\\n");
} else {
    printf("impair\\n");
}
```

## Exercice 4 — ordre des else if
Donner l'affichage exact du programme suivant :
```c
int t = 12;
if (t > 20) {
    printf("chaud\\n");
} else if (t > 10) {
    printf("doux\\n");
} else if (t > 0) {
    printf("frais\\n");
} else {
    printf("froid\\n");
}
```

## Exercice 5 — deux if séparés (attention: pas else)
Comparer avec un if/else if.
Donner l'affichage exact du programme suivant :
```c
int a = 4;
if (a >= 0) {
    printf("non-negatif\\n");
}
if (a % 2 == 0) {
    printf("pair\\n");
}
```

## Exercice 6 — if/else if vs deux if (cas exclusif)
Donner l'affichage exact du programme suivant :
```c
int v = 3;
if (v > 0) {
    printf("positif\\n");
} else if (v % 3 == 0) {
    printf("multiple de 3\\n");
}
```

## Exercice 7 — deux if (cas cumulable)
Donner l'affichage exact du programme suivant :
```c
int v = 9;
if (v > 0) {
    printf("positif\\n");
}
if (v % 3 == 0) {
    printf("multiple de 3\\n");
}
```

## Exercice 8 — attention à l'égalité
Donner l'affichage exact du programme suivant :
```c
int y = 100;
if (y > 100) {
    printf("strictement plus grand\\n");
} else if (y == 100) {
    printf("egal\\n");
} else {
    printf("strictement plus petit\\n");
}
```

## Exercice 9 — ordre des tests qui se recouvrent
Donner l'affichage exact du programme suivant :
```c
int k = 8;
if (k >= 0) {
    printf("A\\n");
} else if (k >= 5) {
    printf("B\\n");
}
```

## Exercice 10 — imbriqué (if dans if)
Donner l'affichage exact du programme suivant :
```c
int a = 2;
int b = 5;
if (a < b) {
    printf("a<b\\n");
    if (b - a == 3) {
        printf("ecart=3\\n");
    }
}
```


## Exercice 11 — if/else if avec plusieurs conditions
Donner l'affichage exact du programme suivant :
```c
int m = 15;
if (m % 2 == 0 && m > 10) {
    printf("A\\n");
} else if (m % 5 == 0 || m == 7) {
    printf("B\\n");
} else {
    printf("C\\n");
}
```

## Exercice 12 — deux if vs if/else if (différence visible)
Donner l'affichage exact du programme suivant :
```c
int z = 0;
if (z == 0) {
    printf("zero\\n");
}
if (z <= 0) {
    printf("negatif ou zero\\n");
}
```

## Exercice 13 — if/else if avec bornes
Donner l'affichage exact du programme suivant :
```c
int note = 14;
if (note >= 16) {
    printf("TB\\n");
} else if (note >= 14) {
    printf("B\\n");
} else if (note >= 12) {
    printf("AB\\n");
} else {
    printf("Passable\\n");
}
```

## Exercice 14 — priorité du premier vrai dans else if
Donner l'affichage exact du programme suivant :
```c
int p = 6;
if (p > 2) {
    printf("X\\n");
} else if (p > 4) {
    printf("Y\\n");
} else {
    printf("Z\\n");
}
```

## Exercice 15 — if/else et plusieurs printf
Donner l'affichage exact du programme suivant :
```c
int q = -3;
if (q >= 0) {
    printf("start\\n");
    printf("q>=0\\n");
} else {
    printf("start\\n");
    printf("q<0\\n");
}
```

# Solutions

## Exercice 1 — if simple
Affichage :
OK

## Exercice 2 — if/else
Affichage :
non-negatif

## Exercice 3 — if/else if/else
Affichage :
impair

## Exercice 4 — ordre des else if
Affichage :
doux

## Exercice 5 — deux if séparés
Affichage :
non-negatif
pair

## Exercice 6 — if/else if vs deux if (cas exclusif)
Affichage :
positif

## Exercice 7 — deux if (cas cumulable)
Affichage :
positif
multiple de 3

## Exercice 8 — attention à l'égalité
Affichage :
egal

## Exercice 9 — ordre des tests qui se recouvrent
Affichage :
A

## Exercice 10 — imbriqué (if dans if)
Affichage :
a<b
ecart=3

## Exercice 11 — if/else if avec plusieurs conditions
Affichage :
B

## Exercice 12 — deux if vs if/else if (différence visible)
Affichage :
zero
negatif ou zero

## Exercice 13 — if/else if avec bornes
Affichage :
B

## Exercice 14 — priorité du premier vrai dans else if
Affichage :
X

## Exercice 15 — if/else et plusieurs printf
Affichage :
start
q<0
