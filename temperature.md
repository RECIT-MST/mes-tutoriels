# temperature

## @showdialog
Ce tutoriel a été créer par:

![RECITMST](https://github.com/recitmstmam/mes-tutoriels/blob/master/images/logomst%20transparant.png?raw=true)

## Étape 1/1

 Nous voulons faire afficher le température lorsque le bouton A est pressé.

 ```blocks
  input.onButtonPressed(Button.A, function () {
    basic.showString("" + (input.temperature()))
})
```

## FÉLICITATIONS

FÉLICITATIONS! il fait chaud