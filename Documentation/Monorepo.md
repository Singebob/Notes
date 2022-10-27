# C'est quoi ? 
*A monorepo is a single repository containing multiple distinct projects, with well-defined relationships*
// TODO: A revoir
Ce qui signifie qu'un monorepo est un repo qui va containir **plusieurs project distinct** mais avec des **relations bien définis**.
![[Pasted image 20221025135451.png|500]] 
## Monorepo != Monolith
> [!TODO]
> Aller plus loin entre les deux 
> https://blog.nrwl.io/misconceptions-about-monorepos-monorepo-monolith-df1250d4b03c

# Problème avec les polyrepos

## Compliquer de partager le code / silos

## Beaucoup de duplication de code 
 Exemple la config d'un projet

## Couteux de changer une libraire tiers
 Compliquer de changer une librairie tiers sur tout les projets
 
 >[!example]
 >Monter de version de springboot sur chaque API
 
 
 
 
## Les outils qui ne sont pas compatibles



# Pourquoi utiliser un monorepo ? 
 
## Ce n'est pas compliqué de lancer un nouveau projet

Le lancement d'un nouveau projet est très simple. Il suffit juste de créer un nouveau dossier/package dans le monorepo et de choisir ses dépendances entre les pacakages du repos actuelle.
## Un commit entre tout les projets

Lors d'une évolution, on a besoin de switcher entre tout nos projets pour ajouter la fonctionnalité. En monorepo, la fonctionnalités est fait avec un commit/PR/MR, ce qui va permettre un rollback facile, mais aussi une mise en production beaucoup plus rapide
## Une seule version de tout

Le changement de version d'une librairies tiers est facilité par les monorepos, car on ne fait la modifiaction qu'a un seul endroit et on est capable de voir tout les impactes très rapidement.
## Facilitation de partage / casser les silots
>[!TODO]
>A voir avec William

# Outil
## Bazel
Google
## Gradle
## Lage
## Lerna
## NX
## Pants
## Rush
## Turborepo
Vercel
>[!TODO]
>Faire une application exemple avec turborepo



- https://monorepo.tools/#what-is-a-monorepo
- https://blog.nrwl.io/misconceptions-about-monorepos-monorepo-monolith-df1250d4b03c
- https://www.maxpou.fr/monorepo-pros-and-cons-fr


