# 01 — Le modèle Halo 2

Halo 2 est un système de preuve à divulgation nulle conçu autour de circuits arithmétiques.
Le dépôt sépare l’interface de circuit dans `halo2_frontend/` du protocole dans `halo2_proofs/`.
Un circuit décrit des relations entre cellules, colonnes et contraintes, pas une suite d’instructions EVM.
Le témoin fournit les valeurs privées tandis que les contraintes définissent ce qui doit être vrai.
Le vérificateur apprend que ces relations sont satisfaites sans recevoir le témoin complet.
La construction utilisée par Zcash évite une cérémonie de paramètres propre à chaque circuit.
Cette propriété ne supprime pas la nécessité d’examiner le circuit et ses entrées publiques.
La qualité d’une preuve dépend d’abord de la fidélité des contraintes au problème réel.

Suite : [colonnes, régions et portes](02-circuits-contraintes.md).
