# Travail reproductible avec **packrat**

Bien que l'utilisation des langages de programmation *open-source* soit de plus en plus acceptée au sein d'organisations historiquement craintives, on entend souvent des critiques face à l'évolution rapide de ces langages et leur manque de stabilité dans un contexte professionnel. Certaines compagnies ont d'ailleurs lancé des produits un peu plus conventionnels pour faciliter l'intégration de *R* en entreprise. J'en conviens, certaines de ces solution fonctionnent bien, assurent un grand niveau de reproductibilité et sont bien adaptées pour les utilisateurs qui recherchent un produit clé en main.

Mon humble opinion est que ce genre de solution commerciale propose certe une facilité de reproductibilité, mais au détriment de l'agilité habituelle à intégrer les toutes dernières versions de librairies toujours en développement actif. La librairie *packrat* assure la reproductibilité d'un projet dans le temps sans n'avoir aucun désavantage collatéral. L'idée derrière *packrat* est d'attacher un projet à ses propres librairies au lieu du comportement habituel par défaut qui est d'utiliser les librairies de l'utilisateur qui exécute le projet.

Ma présentation se veut donc un tour d'ensemble de la librairie *packrat*, de son intégration dans RStudio et de l'interraction qu'il peut y avoir entre l'utilisation combinée de *packrat* et *Git* dans un même projet.