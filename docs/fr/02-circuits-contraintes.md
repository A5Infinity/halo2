# 02 — Colonnes, régions et portes

`halo2_frontend` expose les briques qui organisent un circuit en colonnes et régions.
Les colonnes de conseil portent des témoins, les colonnes fixes des constantes et les instances les entrées publiques.
Les sélecteurs activent des portes sur certaines lignes du domaine.
Une porte exprime une identité polynomiale qui doit s’annuler lorsque son sélecteur est actif.
Les régions rendent explicite l’endroit où un composant assigne ses cellules.
Les contraintes d’égalité relient des valeurs copiées entre zones du circuit.
Cette discipline évite de confondre allocation d’un témoin et preuve d’une relation.
Lors d’une revue, chaque valeur privée doit être suivie jusqu’à la contrainte qui la lie au résultat public.

Suite : [tables de consultation](03-lookups.md).
