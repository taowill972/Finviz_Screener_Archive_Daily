# Finviz_Screener_Archive_Daily

Archive quotidienne **point-in-time** du screener Finviz filtre (strategie
52w-high momentum). Projet distinct, alimente automatiquement par le job
`after_close` du systeme Alpaca_52w_auto (VPS) apres chaque cloture US.

Chaque fichier `AAAA-MM-JJ_finviz_screener.md` contient :
- l'URL exacte du screener filtre du jour ;
- les filtres actifs decodes avec leurs valeurs ;
- le nombre d'actions ;
- le tableau complet tel qu'affiche sur le site (toutes lignes, toutes
  colonnes, toutes pages).

Finalite : constituer un historique du filtrage pour de futurs backtests
d'optimisation. Le dossier PC eponyme est un clone de ce depot (pull
quotidien planifie).
