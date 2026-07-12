# MongoDB : les limites de $lookup

`$lookup` fait une jointure gauche entre collections, mais ne profite pas toujours des index dans les pipelines complexes — toujours vérifier avec `explain()`.
