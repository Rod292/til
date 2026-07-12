# Mongoose : lean() pour les lectures

`Model.find().lean()` renvoie des objets JS bruts au lieu de documents Mongoose hydratés : nettement plus rapide quand on ne fait que lire.
