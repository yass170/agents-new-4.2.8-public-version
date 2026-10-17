# Agents — version 4.2.8 — version publique

Structure d’un cadre d’agents, comprenant des catégories de gouvernance, de style et de workflows.

## Confidentialité et anonymisation

Ce dépôt est une présentation publique de la structure du projet. **Tous les contenus d’origine des fichiers conservés ont été supprimés pour des raisons de confidentialité.** Les fichiers de code, de configuration, de migration SQL, de tests, de gouvernance et les artefacts d’ingénierie conservés contiennent uniquement la phrase « Contenu anonymisé ». Cette règle s’applique aussi aux exemples et aux modèles.

Les données, secrets, fichiers binaires, dépendances embarquées, résultats générés, wireframes, journaux et dossiers de documentation de work ont été exclus. Les dossiers `.agent` et `.agents`, les fichiers `AGENTS.md` et les métadonnées Git d’origine sont absents. Les noms susceptibles de révéler une entreprise, une personne, un client ou un système interne ont été remplacés par des noms génériques.

Seuls ce README et les présentations d’architecture ont un contenu explicatif : ces textes ont été entièrement rédigés pour cette version publique, sans reprendre les détails internes. L’historique Git public commence avec cette version anonymisée.

## Fonctionnement général

Le dossier `new-4.2.8/framework/` présente les catégories de gouvernance, les workflows, les compétences, les modèles et les exemples. La gouvernance définit un cadre général ; les workflows organisent les étapes ; les compétences et modèles servent de supports. Les règles et les champs des fichiers sont intégralement masqués. Le dossier technique d’origine a été renommé `framework`.

Formats techniques représentés : Python, JavaScript, configuration textuelle.

La copie permet de parcourir l’organisation technique et d’identifier les familles de composants. **Elle ne permet ni d’exécuter ni de reconstruire le projet.** Les configurations et les migrations sont volontairement incomplètes et ne doivent pas être lancées.

## Organisation

- `new-4.2.8/`

Les catégories de la version 4.2.8 :

- `new-4.2.8/framework/examples/`
- `new-4.2.8/framework/governance/`
- `new-4.2.8/framework/references/`
- `new-4.2.8/framework/scripts/`
- `new-4.2.8/framework/skills/`
- `new-4.2.8/framework/templates/`
- `new-4.2.8/framework/workflow/`

Les noms `module-…` et `fichier-…` désignent des éléments renommés. Les extensions des fichiers textuels conservés indiquent leur format d’origine.

Consulter [ARCHITECTURE.md](ARCHITECTURE.md) pour la présentation générale.
