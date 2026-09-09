# claude-skills

Skills pour Claude, écrites pour le travail juridique et pour la construction d'outils d'aide à la rédaction en droit administratif français.

## Contenu

| Skill | Objet |
|---|---|
| [`raisonnement-juridique-administratif`](skills/raisonnement-juridique-administratif) | Raisonnement du juge administratif : analyse du dossier, conclusions, moyens et arguments, questions préalables, grille propre à chaque contentieux (excès de pouvoir, fiscal, indemnitaire, appel, cassation), office du juge, syllogisme et motivation, autorité des décisions, structure de la décision. Avec une référence sur le contentieux fiscal, articles vérifiés sur Légifrance. |
| [`examen-consultatif-projet-de-texte`](skills/examen-consultatif-projet-de-texte) | Examen juridique d'un projet de texte normatif, dans l'ordre consultatif : compétence, base légale, consultations, constitutionnalité, conventionnalité, articulation avec le droit existant, légistique, outre-mer, entrée en vigueur. |
| [`legistique-modifications-de-textes`](skills/legistique-modifications-de-textes) | Lire, appliquer et rédiger les instructions par lesquelles un texte en modifie un autre ; décompte des alinéas, désignations composées, consolidation, tableau à trois colonnes. |

Les trois skills se complètent : l'examen consultatif appelle la légistique des modifications pour lire un texte modificatif ; le raisonnement administratif vaut pour le contentieux et ne se transpose pas au consultatif.

## Installation

Copier le dossier de la skill dans le répertoire des skills de votre environnement Claude, ou en reprendre le contenu dans une skill de compte. Le fichier `SKILL.md` se suffit ; les fichiers `references/` apportent la profondeur quand l'environnement les charge.

## Avertissement

Ces skills sont des outils d'aide à l'analyse et à la rédaction. Elles ne dispensent d'aucune vérification, et les décisions de justice comme les avis relèvent de la seule responsabilité de ceux qui les rendent. Elles constituent un travail personnel et n'engagent aucune institution.

## Licence

MIT. Voir [LICENSE](LICENSE) et [NOTICE.md](NOTICE.md) pour les attributions.
