# de-a-jouer

## @showdialog
Ce tutoriel a été créer par :
 
![RECITMST](https://github.com/recitmstmam/mes-tutoriels/blob/master/images/logomst%20transparant.png?raw=true)
  
## @showdialog
 
Transformez votre Micro:bit en un dé à 6 faces!
 
![De](https://github.com/recitmstmam/mes-tutoriels/blob/master/images/de.gif?raw=true)

## Étape 1/3

En premier il faut créer une variable que tu nommeras « Chiffre »

![Créer une variable](https://github.com/recitmstmam/mes-tutoriels/blob/master/images/Cr%C3%A9ation%20de%20variable.gif?raw=true)

## Étape 2/3

Par la suite, on désire que lorsqu'on appuie sur le bouton A, le Micro:bit ``||math:choisisse un nombre au hasard entre 1 et 6||`` et que ce nombre soit attribuer à la variable « Chiffre »

```blocks
let Chiffre = 0
input.onButtonPressed(Button.A, function () {
    Chiffre = randint(1, 6)
})
```

## Étape 3/3

Pour finir, on désire afficher le monbre de la ``||variable:chiffre||`` pendant une seconde et effacer l'écran par la suite.

```blocks
let Chiffre = 0
input.onButtonPressed(Button.A, function () {
    Chiffre = randint(1, 6)
    basic.showString("" + (Chiffre))
    basic.pause(1000)
    basic.clearScreen()
}) 
```

## @showdialog

FÉLICITATIONS, tu as maintenant ton propre dé à jour Micro:bit.  Tu pourrais comme nouveaux défis faire un dé à 12, 20 ou 50 nombres ou encore, tu pourrais avoir trois dés à jouer différents sur ton Micro:bit.  À toi d'imaginer comment tu peux réaliser ce défi.