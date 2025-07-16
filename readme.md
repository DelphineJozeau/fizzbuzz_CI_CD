Mise en place d'une CI intégration continue sur GitHub avec le projet Fizzbuzz

Dans cet exercice j'ai :

- Un projet Github contenant un petit code JavaScript (Node.js), le fizzbuzz.js
- Mis en place un envoronnement de test
- lancé les tests avec npm run test
- Mise en place d’une CI avec GitHub Actions.
- Exécuté une CI sur le projet : Cela consiste à rajouter un fichier .github/workflows/test.yml dans le dépôt Git.
- Ce dernier est une description des instructions que doit faire la CI afin de valider le projet.


    si le nombre est divisible par 3 : on écrit Fizz
    si le nombre est divisible par 5 : on écrit Buzz
    si le nombre est divisible par 3 et par 5 : on écrit Fizzbuzz
    sinon : on écrit le nombre

Nous allons donc créer une nouvelle branche (git checkout -b fizzbuzz-15) où nous allons rajouter un nouveau test dans notre fichier fizzbuzz.test.js: