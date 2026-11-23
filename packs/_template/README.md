# Template de pack SignLearn

Ce dossier décrit le format attendu pour un futur pack. L’exemple `sign-record.example.json` est fictif et bloqué.

Un enregistrement peut être préparé pendant la revue, mais l’application ne doit charger un média que lorsque sa provenance, sa licence commerciale, le consentement des personnes filmées, les éléments de tiers et la validation linguistique sont approuvés.

Statuts recommandés :

- `blocked-pending-clearance` : aucune licence ou preuve de consentement complète ;
- `needs-linguistic-review` : droits suffisants mais relecture linguistique manquante ;
- `approved-commercial` : vidéo autorisée pour l’application commerciale ;
- `approved-derived-only` : seul le dérivé explicitement autorisé peut être publié ;
- `rejected` : source ou contenu incompatible.

Le statut `approved-commercial` ne doit être utilisé qu’avec une fiche de provenance conforme à `schemas/asset-provenance.schema.json` et des preuves archivées hors des données personnelles publiques.
