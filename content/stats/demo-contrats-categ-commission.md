---
title: "DEMO : Contrats-commision annuelle par / code Catégorie"
draft: false
weight: 180

mode_bootstrap: false

detail_tableau: true
detail_tableau_court: true
detail_categ: false
detail_total: true

detail_debug: false
detail_debug_verbose: false

numcol_categ: 4
categ_libelle_decalage: 1
numcol_stats: [11, 13, 19]
numcol_date_effet: 7
numcol_date_fin: 8

graph_legende: false

graph_type: "pie"
graph_default: 2
---

{{% csvdata-stats csvfile="csv/demo-contrat-test.csv" %}}
