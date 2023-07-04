# mob101

Présentation du mob (ensemble) programming

## Concept

Le <b>[mob programming](https://en.wikipedia.org/wiki/Mob_programming)</b> est une approche collaborative de dévéloppement logiciel.

C'est une extension du pair programming, technique plébiscitée par l'Extreme Programming.

<img src="https://exmachina.ch/images/2020/09/MobProgramming.png" />

Points communs :
- Une seule personne intéragit avec le code
- Système de roulement

Points différenciants :
- +2 personnes
- Pas obligatoire d'être un dévéloppeur pour participer (design, produt, QA etc...)


## Roles

Les rôles tournent, les responsabilités également.

Le temps de chaque tour doit être défini avec les membres de la session.

En règle générale, entre 7 et 15 minutes. 

Il peut être intéressant de coupler une session de mob programming avec la [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique).


<img src="https://images.prismic.io/sketchplanations/62e61034-b66a-4ede-a5db-a5cbc39d55e7_SP+587+-+The+Pomodoro+technique.jpg?auto=compress,format"> 

### Driver

Le Driver tient le clavier. Il éxécute ce que le <b>co-pilot</b> lui demande.

*Difficulté : 1/5*

### Co-pilot

Le Co-pilot indique au Driver ce qu'il doit écrire.

Il fait également l'arbitrage et la synthèse des Navigators.

*Difficulté : 5/5*

### Navigator(s)

Les Navigators ont pour rôle de donner de la hauteur à la session.

Pour atteindre ce but, ils peuvent :

- Communiquer des nouveaux raccourcis
- Lire de la documentation et anticiper les refactors
- Vérifier l'homogénéité des cas de tests
- Indiquer des fonctionnalités de l'IDE
- *liste non exhaustive*

*Difficulté : 3/5*


## FizzBuzz

### Règles

Le test Fizz-Buzz est issu d'une méthode permettant d'apprendre les divisions aux enfants.

Pour les nombres entre 1 et 20 :

- si le nombre est divisible par 3 : on écrit Fizz
- si le nombre est divisible par 5 : on écrit Buzz
- si le nombre est divisible par 3 et par 5 : on écrit Fizzbuzz
- sinon : on écrit le nombre

### Outil

[mob.sh](https://mob.sh)

```bash
curl -sL install.mob.sh | sh
```

