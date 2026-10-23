# claude-skills

English version: [README.en.md](README.en.md)

Skills pour Claude, écrites pour le travail juridique et pour la construction d'outils d'aide à la rédaction en droit administratif français.

## Contenu

| Skill | Objet |
|---|---|
| [`raisonnement-juridique-administratif`](skills/raisonnement-juridique-administratif) | Raisonnement du juge administratif : analyse du dossier, conclusions, moyens et arguments, questions préalables, grille propre à chaque contentieux (excès de pouvoir, fiscal, indemnitaire, appel, cassation), office du juge, syllogisme et motivation, autorité des décisions, structure de la décision. Avec une référence sur le contentieux fiscal, articles vérifiés sur Légifrance. |
| [`identification-des-moyens-contentieux-administratif`](skills/identification-des-moyens-contentieux-administratif) | Relever les conclusions, les moyens et les questions préalables d'un dossier contentieux à partir des mémoires : taxinomie des moyens par type de contentieux, ancrage de chaque moyen sur un passage cité du mémoire et vérification mécanique de la citation, garde-fous, ordre d'examen, examen d'office sur liste fermée, moyens d'ordre public, mesures tirées de l'open data de la juridiction administrative (un million de décisions). |
| [`ordonnances-juridictionnelles-contentieux-administratif`](skills/ordonnances-juridictionnelles-contentieux-administratif) | Rédiger une ordonnance de tribunal administratif, de cour administrative d'appel ou du Conseil d'État : tous les cas (désistement, incompétence, non-lieu, irrecevabilité, série, moyens manifestement infondés, appel manifestement infondé, non-admission des pourvois, référés, compétence, instruction, exécution), le texte en vigueur de chaque fondement du code de justice administrative, ce que les motifs doivent établir, la présentation formelle propre à chaque niveau de juridiction, les signaux à chercher dans un dossier et les contrôles avant signature ; fréquences observées dans l'open data. |
| [`examen-consultatif-projet-de-texte`](skills/examen-consultatif-projet-de-texte) | Examen juridique d'un projet de texte normatif, dans l'ordre consultatif : compétence, base légale, consultations, constitutionnalité, conventionnalité, articulation avec le droit existant, légistique, outre-mer, entrée en vigueur. |
| [`legistique-modifications-de-textes`](skills/legistique-modifications-de-textes) | Lire, appliquer et rédiger les instructions par lesquelles un texte en modifie un autre ; décompte des alinéas, désignations composées, consolidation, tableau à trois colonnes. |
| [`tableau-trois-colonnes`](skills/tableau-trois-colonnes) | Construire, vérifier ou corriger le tableau à trois colonnes (droit en vigueur, texte du projet, texte consolidé) d'un projet de texte : désigner sans recopier, distinguer l'ancrage de la cible, une ligne par opération, colonne 3 toujours remplie, incidents signalés plutôt qu'appliqués au jugé. |
| [`relecture-legistique`](skills/relecture-legistique) | Relecture de la forme d'un projet de texte au regard des fiches du guide de légistique : langue, temps et mode, sigles, termes juridiques, articles et alinéas, ponctuation, typographie du Journal officiel, visas, renvois. Rendu sous forme de tableau d'écarts, chacun fondé sur une fiche. |

Les skills se complètent : l'examen consultatif porte sur le fond du projet et appelle la légistique des modifications pour lire un texte modificatif ; le tableau à trois colonnes en rend compte, article par article, et sert de support à l'examen ; la relecture légistique ne porte que sur la forme ; le raisonnement administratif vaut pour le contentieux et ne se transpose pas au consultatif ; l'identification des moyens en est la première étape, celle qui établit ce que le dossier contient avant tout raisonnement ; les ordonnances en sont l'issue courte, quand le dossier ne demande ni instruction ni audience.

## Installation

Copier le dossier de la skill dans le répertoire des skills de votre environnement Claude, ou en reprendre le contenu dans une skill de compte. Le fichier `SKILL.md` se suffit ; les fichiers `references/` apportent la profondeur quand l'environnement les charge. La version anglaise de la skill des ordonnances (`SKILL.en.md`) est en cours.

## Avertissement

Ces skills sont des outils d'aide à l'analyse et à la rédaction. Elles ne dispensent d'aucune vérification, et les décisions de justice comme les avis relèvent de la seule responsabilité de ceux qui les rendent. Elles constituent un travail personnel et n'engagent aucune institution.

## Licence

MIT, © Armadillo4Ever. Voir [LICENSE](LICENSE) et [NOTICE.md](NOTICE.md) pour les attributions.
