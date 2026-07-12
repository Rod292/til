# shell : trap pour nettoyer à la sortie

`trap "rm -rf $TMP" EXIT` garantit le nettoyage même quand le script échoue.
