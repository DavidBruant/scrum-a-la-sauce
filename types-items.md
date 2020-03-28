# Items

Le backlog est composé d'items

Un item est toute chose sur laquelle **l'équipe de production** va **passer du temps**. Il s'agit donc un objet qui sera **discutable** et **priorisable**.

Tout item devrait avoir une "definition of done", c'est-à-dire des critères pour qui permettent de dire que l'on est passé de "à faire" à "fait". Le statut "fait" devrait être démontrable.

Les items sont "SMART" (TODO trouver la définition en ligne), mais notamment : 
- indivisible
- 

## User story

Une user story est un type d'item dont le statut "fait" rajoute une valeur pour au produit pour les stakeholders.

Le produit avant et après avoir la user story a une valeur en plus, même petite. Par exemple, la correction d'un petit bug, l'implémentation d'un autocomplete pour réduire les erreurs de saisie, la traduction d'une interface (ou juste de certains écrans pour commencer), etc.


## Tâche

Une tâche est un type d'item qui améliore les conditions de travail de l'équipe de production, mais qui ne rajoute pas de valeur démontrable au produit. Il peut s'agir de la mise en place d'intégration continue, de la mise en place d'outils de qualité de code (ESLint, etc.), d'un refactoring, de déploiement via Docker, une migration de base de données, etc.

(Ceci présuppose une séparation claire entre le "code" et le "produit", alors que dans le cas d'une bibliothèque de code, le code est le produit. TODO : clarifier)


## Apprentissage

Un apprentissage est un type d'item.

Parfois, une *user story* nécessite d'avoir certains connaissances/compétences que personne au sein de l'équipe de production n'a. Il peut s'agir de SEO, d'accessibilité, de Machine Learning, de JavaScript, de 3D, de calcul sur GPU, etc.
Dans beaucoup de cas, il est possible d'insérer l'apprentissage dans le développement de la *user story*, mais parfois, il faut plus de temps ou a minima, le temps pour connaître suffisamment est inconnu.

On créé alors un item d'apprentissage. La démonstartion du "fait" sera peut-être de montrer que l'on a su refaire une tutoriel, obtenu les badges correspondants d'une plateforme en ligne, montrer que l'on a su recréer un petit quelque chose différent du tutoriel, etc.
