---
name: Demande d'aide / Bug
about: J'ai un bug, il est comme-ci, comme-ça, qu'est-ce que je fais ?
title: ''
labels: ''
assignees: ''

---

⚠️  Penses à supprimer les sections dont tu n'as pas besoin pour rédiger ton issue.  
Modifie celles qui ont un intérêt.  
Une issue bien formatée trouvera plus rapidement une solution !

## Projet
On met l'url du projet github et la branche pour qu'on puisse checker le code
[Dépot](https://github.com/tonprojet) branche `main`.  
⚠️  **On n'oublie pas de push son travail afin que le problème soit visible sur Github**.

## Labels
On pense à mettre des labels sur l'issue pour en faciliter la compréhension de prime abord.

## Décrire le bug
Une **claire** et **concise** description de ce qu'est le bug.

## Pour reproduire
Les étapes pour reproduire le bug :
1. Aller dans '...'
2. Cliquer sur '....'
3. Scroller à  '....'
4. On voit l'erreur

## Fonctionnement attendu
Une **claire** et **concise** description de ce qui **aurait dû** se passer
## Le code concerné
On met un extrait du bout de code concerné en utilisant les triple back ticks **et** le langage concerné pour la coloration syntaxique, ex : 
```js
//app/model/test.js
console.log("hello world");
```
Si c'est déjà commité, on peut aussi mettre le lien github direct du fichier incriminé.

## Quelle est l'erreur
Ici on met l'erreur **en entier** en utilisant les triple backticks, ex : 
```
/home/monProjet/index.js:9
test.error = "Hello"
^
ReferenceError: test is not defined
    at Object.<anonymous> (/home/monProjet/index.js:9:1)
?[90m    at Module._compile (internal/modules/cjs/loader.js:1138:30)?[39m
?[90m    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1158:10)?[39m
?[90m    at Module.load (internal/modules/cjs/loader.js:986:32)?[39m
?[90m    at Function.Module._load (internal/modules/cjs/loader.js:879:14)?[39m
?[90m    at Function.executeUserEntryPoint [as runMain] (internal/modules/run_main.js:71:12)?[39m
?[90m    at internal/main/run_main_module.js:17:47?[39m
```

## Qu'avez vous testé ?
Exemple :
1. J'ai cherché "..." sur google
2. J'ai console.log "..." à plusieurs endroits.
3. J'ai "..."

## Screenshots
Si ça s'y prête, on ajoute des captures d'écran pour aider à expliquer le problème
Tu peux les copier coller directement, ou les faires glisser dans la zone de texte !
Utilise un outil de capture d'écran sur ton OS, ça peut te faciliter la vie !
