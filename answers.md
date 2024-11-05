# Answers of Niklas Weis nikcoer012

## Basics

### Task 1

On trouve deux dossiers et un fichier clônés du répertoire. Un permier dossier "visible" contient/ va contenir toutes les images utillisées. Le fichier "visible" est le answers.md cloné. Le fichier .git "invisible" contient toutes les informations necessaires et l'adresse à la création locale du répertoire, il stocke aussi toutes les informations sur les branches et les commits.

### Task 2

En regardant avant et après git status change car nous avons un fichier de plus qui était "Untracked", le README.md. git log --oneline ne change pas car aucun commit n'a encore été fait.

### Task 3

Après avoir executé la commande "add" le fichier README.md est passé du working directory  au Staging area. Nous le voyons aussi en regardant le git status, "Changes to be commited:" new file:   README.md

### Task 4

Nous modifions le fichier README.md. Quand on demande git status one retrouve toujours le fichier README.md sous "Changes to be committed:"de l'étape "add" et est prêt à être commit sur le local git repository. Mais nous avons aussi "Changes not staged for commit:" avec le fichier README.md en dessous ce qui indique qu'il est différent de celui qui est "prêt" à être commit.

### Task 5

La chaîne de caractères (short hash) au début signifie une clé unique à chaque commit pour qu'il n'y aie aucune confusion lorsqu'on doit rechercher des anciens commits. HEAD consitue tout ce qu'on a/avait dans le Staging area est sont les éléments prêts à commit. Et le main est dans le local git repository et est notre master branche. Après les paramthèses se trouve le commentaire défini avec le commit spécifique.

### Task 6

Les réponses étaient disparuent... Lorsqu'on checkout un commit ce sera celui là qui va être pris du Local repository sur le Staging area et en conséquence que les versions de fichier et fichers vont être disponibles lorsque nous étions au premier commit.

Checkout le main va nous mettre le dernier commit réalisé dans le Staging area. Nous allons retrouver toutes nos modifications et nouveaux fichiers.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)

1 - name of branch

2 - short hash

3 - commit comment 

4 - user who comitted

5 - version hisotry of main

6 - last commit of seocndary branch 

7 - tertiary branch

8 - last commit of main branch

9 - secondary branch

10 - main branch