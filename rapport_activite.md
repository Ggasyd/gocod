**Titre : Rapport d'Activité Sprint 1**

**Date : 12/11/2023**

**Participants : ABDOULAYE Izedine, ADEROMOU Ariel, GAGNON Gasyd, SEFOU IBIKOUNLE Anifath**

**Objectifs :**

- **Compléter les fonctions CRUD dans le back-end :**

    - Actions CRUD pour le developpeur (crud_operations)

- **Implémenter des fonctionnalités basées sur MongoDB :**

    - Actions Create, Authenticate et read user informations pour l'administrateur,

    - Actions Update,Delete et List projects pour l'utilisateur,

    - Actions Create, Read, List, Delete et Star Templates pour l'utilisateur

**Réalisations :**

   - Creation d'une variable containerEnv pour définir le pythonpath par défaut au conteneur,

   - Creation de branches pour chacun des membres du groupe sur git,

   - Realisation des CRUD pour l'utilisateur,

   - Realisation de Create, authenticate et read des utilisateurs pour les administrateurs,

   - Realisation de Update, Delete et List les projects pour les utilisateurs,

   - Realisation de Create, Read, List et Delete les templates pour les utilisateurs

**Problèmes rencontrés**

   - Problèmes de git:pull, push,pull request et merge branch.

   - Problème avec la fonction et le test star_template.


**Actions correctives**

   Il faut faire les git pull en dehors du conteneur dans le dossier du projet et une fois qu'on a récupéré la version à jour,on ouvre le conteneur.
   Il fallait modifier la fonction test_templates. L'argument passé à la fonction test star_template dans est le template name qui est un string. Il fallait corriger et passer en argument  

**Conclusion**

   Toutes les fonctions s'exécutent bien et les tests passent normalement.
   Il faudrait pousser les fichiers sur git au fur et à mesure et avoir un suivi de notre activité sur git un peu plus rigoureux. Lire attentivement les fonctions déjà mises en place et comprendre leur fonctionnement.

   
