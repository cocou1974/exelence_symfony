# mexico_symfony_blog

## Les 3 étapes pour créer une table:
- Créer l'entité 
    - [symfony console make:entity Contact]
    - [symfony console make:user]
- Se baser sur l'entité pour générer le code SQL (Faire la migration) 
    - [symfony console make:migration]
- Exécuter le code SQL généré (Migrer les données)
    - [symfony console doctrine:migrations:migrate]
