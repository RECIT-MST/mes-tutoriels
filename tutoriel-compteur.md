# Tutoriel compteur

## Introduction @unplugged

Ce tutoriel a été créer par :
 
![RECITMST](https://drive.google.com/uc?id=1YsdDZIAnwl9ZNGyIEu6d0xQoCtZ8eRXa)
  
## Introduction @unplugged
 
Construire ton compteur!
 
![Compteur](https://drive.google.com/uc?id=1H0uVMmrqvSdWm0xzozLm1oho0AgUch62)

## Étape 1/6 @showhint

En premier il faut créer un variable que tu nommeras "Nombre"

![Créer une variable](https://drive.google.com/uc?id=1xpWsU0MOqC92aGmJPbaPUdsU_XF7xsrQ)

## Étape 2/6 @showhint

Par la suite, il faut mettre notre compteur à zéro lors du démarrage du Micro:bit.  Pour ce faire, tu dois ajouter un bloc dans le bloc " Au démarrage"

```blocks
let Nombre = 0
Nombre = 0
```

## Étape 3/6 @fullscreen

Pour que ton Micro:bit se transforme en compteur, tu veux qu'à chaque fois que tu appuies sur le bouton A, le nombre augmente de 1 et qu'il s'affiche sur l'écran.  Tu auras besoin de 3 blocs pour réaliser cette étape.

```blocks
input.onButtonPressed(Button.A, function () {
    Nombre += 1
    basic.showNumber(Nombre)
})
```
## Étape 4/6 @showhint

Si tu fais une erreur dans ton compte, tu aimerais pouvoir appuyer sur le bouton B pour soustraire 1 au chiffre actuel.  Tu peux copier les blocs de l'étape précedente et modifier deux éléments pour y arriver.

```blocks
input.onButtonPressed(Button.B, function () {
    Nombre += -1
    basic.showNumber(Nombre)
})
```
### Markdown Sample

## Introduction @unplugged

Construire ton compteur!
 
![Compteur](https://drive.google.com/uc?id=1H0uVMmrqvSdWm0xzozLm1oho0AgUch62)


## Étape 5/6

Il serait pratique que tu puisses remettre à zéro ton compteur en appuyant sur les boutons A+B en même temps.  Tu peux réussir cette étape seule maintenant.

```blocks
input.onButtonPressed(Button.AB, function () {
    Nombre = 0
    basic.showNumber(Nombre)
})
```

## Étape 6/6 @showhint

FÉLICITATIONS!  Tu as réaliser ton propre compteur avec Micro:bit.  Un nouveau défi serait de compter par bon de 5, de 10 ou plus.  Es-tu prêt à relever ce défi ?