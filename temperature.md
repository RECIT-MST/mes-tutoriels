# temperature

## @showdialog
Ce tutoriel a été créer par :
 
![RECITMST](https://github.com/recitmstmam/mes-tutoriels/blob/master/images/logomst%20transparant.png?raw=true)

## Étape 1/1

Premièrement, ajouter dans l'événement ``||basic:toujours||`` le bloc « afficher texte » et également le bloc correspondant à la température

```blocks
basic.forever(function () {
    basic.showString("" + (input.temperature()))
})
```
## Félicitaiton!