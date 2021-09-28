# afficher-mot

## @showdialog
Ce tutoriel a été créer par:

![RECITMST](https://drive.google.com/uc?id=1YsdDZIAnwl9ZNGyIEu6d0xQoCtZ8eRXa)
  
## @showdialog

Construis ton compteur!

![Afficher - un - mot](https://drive.google.com/uc?id=12b27EdxCzUXcN1cO107THvChOvC6aqNp)

## Étape 1/2

Tu dois faire défiller le mot de ton choix sur ton Micro: bit.Pour se faire, tu dois placer le bloc`` || basic: afficher texte "Hello" || `` dans l'événement ``||basic:toujours||``.  Par la suite, remplace le mot "Hello" par le mot de ton choix.

```blocks
basic.forever(function () {
    basic.showString("Hello")
})
```

## Étape 2/2

Pour éviter que le texte s'affiche à nouveau trop rapidement, tu peux ajouter ``||basic:une pause||`` de 1 seconde.

```blocks
basic.pause(100)
```

## @showdialog

FÉLICITATIONS!  Tu peux maintenant faire défiller tout le texte que tu désires sur ton Micro:bit.