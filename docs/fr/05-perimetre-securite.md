# 05 — Périmètre, sécurité et vérification

Une preuve valide établit seulement les contraintes effectivement encodées par le circuit.
Elle ne garantit ni la pertinence des entrées publiques ni l’absence d’erreur dans le modèle métier.
Les paramètres, domaines et stratégies de vérification doivent correspondre à ceux du prouveur.
Les gadgets réutilisables réduisent la duplication mais transmettent aussi leurs hypothèses aux circuits appelants.
Le dépôt contient des exemples, benches et suites de tests pour confronter ces hypothèses.
Ce parcours couvre `halo2_frontend/`, `halo2_proofs/` et les mécanismes de circuit, lookup et transcript.
Il ne constitue ni un audit cryptographique ni une preuve de sécurité d’une application utilisatrice.
Aucune installation, compilation ou exécution n’a été effectuée ; les tests amont restent la référence de validation.
