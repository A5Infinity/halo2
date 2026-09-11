# 04 — Engagements et transcript

Le prouveur engage des polynômes avant que les défis aléatoires ne soient dérivés.
Le transcript applique la transformation de Fiat–Shamir pour rendre le protocole non interactif.
L’ordre d’absorption des engagements, points et évaluations fait partie du protocole.
Une sérialisation ambiguë ou un défi réutilisé fragiliserait la séparation des étapes.
`halo2_proofs/` porte cette orchestration ainsi que les stratégies d’ouverture.
Les engagements cachent les polynômes tout en permettant de vérifier leurs évaluations annoncées.
Le vérificateur reconstruit les défis à partir du même transcript.
La compatibilité exige donc une convention identique de part et d’autre jusque dans les encodages.

Suite : [périmètre et vérification](05-perimetre-securite.md).
