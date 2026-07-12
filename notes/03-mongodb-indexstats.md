# MongoDB : $indexStats pour repérer les index inutilisés

L’agrégation `{ $indexStats: {} }` montre le nombre d’accès par index — pratique pour repérer ceux qui ne servent jamais avant de les supprimer.
