# Documentation du projet git

## Initilisation du dépot

```bash
git init
git remote add origin SSH_URL du repo
git branch -M main
git push -u origin main
```

## Rediger un commit

```
titre du commit

Description de notre commit avec des information sur l'evolution du projet
```

## Envoyer un commit sur le dépot distant

```bash
git commit -m "titre du commit et sous titre"
git push
```

## Creation d'une branche

```bash
$ git checkout -b develop
```

pour les bonne pratique,on va integrer la notion de revue de code,

```bash
$ git checkout -b feature/nom_de_la_feature
```

## Fusionner une branche

```bash
$ git checkout main
$ git merge develop
```

## Afficher les branches

```bash
$ git branch
```

## Supprimer une branche

```bash
$ git branch -d develop
```

## Afficher les commits

```bash
$ git log
```

## Afficher les changements

```bash
$ git status
```

## Afficher les différences

```bash
$ git diff
```

## Cloner un dépot

```bash
$ git clone SSH_URL du repo
```

## Afficher les branches distantes

```bash
$ git branch -r
```

## Afficher les branches locales et distantes

```bash
$ git branch -a
```

## Afficher les tags

```bash
$ git tag
```

## Afficher les commits d'une branche

```bash
$ git log develop
```

## Afficher les commits d'un fichier

```bash
$ git log -- filename
```

## Afficher les commits d'un auteur

```bash
$ git log --author="nom de l'auteur"
```

## Afficher les commits d'une période

```bash
$ git log --since="date de début" --until="date de fin"
```

## Afficher les commits avec un message spécifique

```bash
$ git log --grep="mot clé dans le message de commit"
```

## Afficher les commits avec des fichiers modifiés

```bash
$ git log --name-only
```

## Afficher les commits avec des différences

```bash
$ git log -p
```

## Afficher les commits avec des statistiques

```bash
$ git log --stat
```

## Afficher les commits avec des graphiques

```bash
$ git log --graph
```
