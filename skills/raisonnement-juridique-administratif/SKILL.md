---
name: raisonnement-juridique-administratif
description: "Modélise le raisonnement du juge administratif français pour l'analyse d'un dossier et la rédaction d'une décision. Utiliser ce skill pour identifier les questions de droit, distinguer conclusions, moyens et arguments, appliquer la grille propre à chaque contentieux (excès de pouvoir, plein contentieux fiscal ou indemnitaire, appel, cassation), traiter les questions préalables et les fins de non-recevoir, construire le syllogisme, apprécier l'autorité d'une décision du Conseil d'État, et rédiger des motifs en style direct conformes aux usages de la juridiction administrative. Ne pas l'utiliser pour le contentieux judiciaire."
metadata:
  license: "mit"
  version: "2026-09-09"
  derive_de: "raisonnement-juridique, Amaury Fouret, licence MIT (contentieux civil)"
---

# Raisonnement juridique administratif

Ce skill guide l'analyse d'un dossier et la rédaction d'une décision devant la juridiction administrative française.

## Périmètre, et ce qu'il ne faut pas faire

Ce skill vaut pour l'ordre administratif : Conseil d'État, cours administratives d'appel, tribunaux administratifs, juridictions administratives spécialisées.

Il ne transpose pas au contentieux judiciaire, et l'inverse est vrai. Le code de procédure civile ne régit pas l'office du juge administratif : ne jamais fonder une motivation administrative sur les articles 4, 6, 7, 9, 12 ou 16 du code de procédure civile, ni sur la structure du jugement civil des articles 454 et 480 du même code. La procédure administrative contentieuse est inquisitoire, l'instruction est dirigée par le juge, et la décision obéit à ses propres règles de forme.

## Règle impérative sur les sources

Ne jamais citer un texte, une décision ou un considérant sans en avoir récupéré le texte intégral. Un extrait tronqué issu d'un résultat de recherche ne suffit pas pour une citation juridique. Cette règle s'applique aux articles de code comme aux motifs de décision.

Ne jamais citer de mémoire un numéro de dossier, une date ou une formation de jugement. Si la référence exacte n'a pas été retrouvée dans un fonds, le dire.

Une source est désignée par sa dénomination exacte, telle qu'elle est identifiée par le moteur de recherche, jamais par un intitulé reconstitué.

## Ordre d'interrogation des sources

1. Le texte applicable, dans sa version en vigueur à la date pertinente, et non dans sa version actuelle lorsque le litige porte sur une décision antérieure.
2. La jurisprudence du Conseil d'État, en commençant par les formations les plus solennelles et les décisions publiées au Recueil.
3. Le cas échéant, le Conseil constitutionnel, la Cour de justice de l'Union européenne, la Cour européenne des droits de l'homme, selon la norme invoquée.
4. La doctrine en dernier lieu, et toujours identifiée comme telle.

Ne jamais se limiter aux décisions récentes d'une seule chambre sans avoir vérifié l'existence d'une décision d'Assemblée ou de Section sur la question.

## 1. Prise en main du dossier

1. Identifier les parties et leur qualité, l'auteur de l'acte attaqué et l'administration défenderesse.
2. Identifier la nature du recours : excès de pouvoir, plein contentieux, référé, et le cas échéant le contentieux spécial applicable.
3. Identifier l'acte attaqué avec précision : nature, auteur, date, portée. Une erreur sur l'identification de l'acte vicie tout le raisonnement.
4. Reconstituer la chronologie : faits, décision, recours administratif éventuel, saisine, délais.
5. Recenser les pièces et les mémoires, en distinguant ce qui est produit de ce qui est seulement allégué.
6. Vérifier d'emblée la compétence de la juridiction, la recevabilité et l'existence d'un litige à trancher.

## 2. Conclusions, moyens, arguments

| Élément | Définition | Traitement |
|---|---|---|
| Conclusions | Ce qui est demandé au juge : annulation, indemnisation, injonction, frais d'instance | Statuer dans le dispositif, sans rien omettre et sans excéder la demande |
| Moyen | Raison de droit ou de fait invoquée au soutien des conclusions | Y répondre dans les motifs, sous réserve de l'économie de moyens |
| Argument | Élément de discussion dépourvu d'effet juridique propre | Ne pas y répondre |

Le juge statue sur toutes les conclusions et seulement sur elles. Statuer au delà des conclusions, ou omettre de statuer sur l'une d'elles, entache la décision.

Les moyens se rattachent à des causes juridiques distinctes, la légalité externe et la légalité interne. Un moyen relevant d'une cause juridique nouvelle, invoqué après l'expiration du délai de recours, est irrecevable, sous réserve des moyens d'ordre public. C'est la règle issue de la jurisprudence Intercopie : en retrouver la référence exacte et le verbatim dans le fonds avant de la citer.

Une quatrième catégorie, distincte des trois précédentes, doit être isolée : les **questions préalables**. Elles se traitent avant le fond et n'ont pas la nature de moyens.

- Le non-lieu à statuer, lorsque les conclusions sont devenues sans objet, notamment par un dégrèvement en cours d'instance ou par l'abrogation de l'acte attaqué.
- Le désistement.
- La forclusion et la tardiveté.
- Les fins de non-recevoir opposées par le défendeur : irrecevabilité de conclusions nouvelles en appel, défaut d'intérêt à agir, absence de recours administratif préalable obligatoire, absence de réclamation préalable en matière fiscale.

Ranger une fin de non-recevoir parmi les moyens du requérant, ou une question de recevabilité parmi les moyens de procédure, fausse le plan de la décision.

Voir `references/conclusions-moyens-arguments.md`.

## 3. La grille propre à chaque contentieux

Le plan des motifs n'est pas le même selon la nature du litige. Choisir la grille avant de qualifier les moyens : une grille mal choisie produit des qualifications fausses.

### Excès de pouvoir et plein contentieux objectif

Deux causes juridiques, dans cet ordre : la **légalité externe**, qui comprend l'incompétence, le vice de procédure et le vice de forme, puis la **légalité interne**, qui comprend le défaut de base légale, l'erreur de droit, l'erreur de fait, l'erreur de qualification juridique, l'erreur manifeste d'appréciation et le détournement de pouvoir.

Les moyens de légalité externe sont les plus souvent négligés : les rechercher expressément.

### Plein contentieux fiscal

Ne pas employer ici les catégories de légalité externe et de légalité interne : elles ne sont pas celles de la matière. Trois temps, dans cet ordre : la **régularité du jugement** lorsque l'acte attaqué est un jugement ; la **procédure d'imposition**, qui ne concerne que la régularité du contrôle et de la rectification ; le **bien-fondé** de l'imposition, assiette, taux, qualification, pénalités.

**Piège caractéristique.** La recevabilité de la réclamation préalable (existence, délai, preuve de l'envoi) n'est **pas** un moyen de procédure d'imposition : c'est une question préalable, qu'elle soit soulevée par le requérant ou opposée par l'administration. La ranger en procédure conduit à répondre au mauvais endroit, et parfois à statuer au fond sur une demande irrecevable.

Le contentieux fiscal a en outre ses règles propres, charge de la preuve, garanties du contribuable, dégrèvement et non-lieu, substitution de base légale, compensation, pénalités, qui relèvent d'un développement séparé : voir `references/contentieux-fiscal.md`.

### Plein contentieux indemnitaire

Les points de la responsabilité, dans cet ordre : le **fait générateur**, faute ou responsabilité sans faute selon le régime applicable ; le **lien de causalité**, direct et certain ; puis **chaque préjudice** invoqué, avec son évaluation. Vérifier au passage la demande préalable d'indemnisation et la prescription quadriennale.

### Appel

La **régularité du jugement** vient en tête, avant le bien-fondé de la solution retenue. Ne pas confondre les deux : la critique de la motivation est un moyen de régularité, la critique de la solution est un moyen de fond.

Identifier les rôles avec soin. L'**appelant** est celui qui saisit la cour et demande l'annulation ou la réformation du jugement, **même lorsqu'il s'agit de l'administration** : ses conclusions sont celles du demandeur à l'instance d'appel. L'**intimé** conclut au rejet de la requête et à la confirmation du jugement. Placer l'annulation du jugement du côté du défendeur est une inversion qui rend toute la suite incohérente.

La simple demande d'annulation ou de réformation du jugement est une **conclusion**, non un moyen : ne pas la faire figurer parmi les moyens.

Vérifier enfin l'irrecevabilité des conclusions nouvelles en appel, et l'effet dévolutif.

### Cassation

Deux ensembles : la **régularité de la décision attaquée**, composition de la formation, motivation, procédure ; et son **bien-fondé**, erreur de droit, dénaturation des pièces ou des faits, erreur de qualification juridique.

Le juge de cassation ne rejuge pas les faits : un moyen qui n'invite qu'à leur réappréciation est inopérant, sauf dénaturation. Distinguer ce qui relève du contrôle de qualification juridique de ce qui relève de l'appréciation souveraine.

## 4. Office du juge administratif

Points structurants, développés dans `references/office-du-juge-administratif.md` :

- La motivation est obligatoire, article L. 9 du code de justice administrative.
- La procédure est inquisitoire : le juge dirige l'instruction, ordonne les mesures utiles et peut demander la production de pièces.
- Le juge relève d'office les moyens d'ordre public. Il en informe préalablement les parties et les invite à présenter leurs observations, article R. 611-7 du code de justice administrative. Omettre cette communication est une cause d'annulation.
- Le juge de l'excès de pouvoir peut se borner à retenir un moyen suffisant pour prononcer l'annulation. Cette économie de moyens connaît des limites, notamment lorsque l'examen d'un autre moyen commande les mesures d'exécution ou l'injonction sollicitée. Trancher ce point explicitement plutôt que par défaut.
- Le juge de plein contentieux se prononce sur la situation à la date de sa décision, le juge de l'excès de pouvoir apprécie en principe la légalité à la date de l'acte. Vérifier la règle propre au contentieux en cause avant de fixer la date d'appréciation.

## 5. Syllogisme et motivation

La motivation s'écrit en style direct, par paragraphes numérotés, à l'indicatif présent. Le « considérant que » est abandonné.

**Majeure.** Énoncer la règle applicable, texte et interprétation jurisprudentielle, dans sa version applicable au litige, en précisant les conditions d'application et le régime de la preuve.

**Mineure.** Appliquer aux faits établis par l'instruction, apprécier les pièces, répondre aux moyens, qualifier juridiquement.

**Conclusion.** Tirer la conséquence, en cohérence avec la majeure et la mineure, et la reprendre au dispositif.

Proscrire les motifs hypothétiques, dubitatifs ou surabondants. Un motif qui ne soutient aucune conclusion n'a pas sa place dans la décision.

Voir `references/syllogisme-et-motivation.md`.

## 6. Autorité des décisions

Deux échelles se combinent, la formation de jugement et le niveau de publication. Elles ne se substituent pas l'une à l'autre : une décision d'Assemblée publiée prime, une décision inédite d'une chambre ne fonde pas à elle seule une solution de principe.

Formations, par autorité décroissante : Assemblée du contentieux, Section du contentieux, chambres réunies, chambre jugeant seule, juge statuant seul et ordonnances.

Publication : publié au Recueil Lebon, mentionné aux tables, inédit. Dans les fonds internes, ces niveaux correspondent aux lettres A, B et C.

Les avis rendus sur demande d'une juridiction, article L. 113-1 du code de justice administrative, ont une autorité propre qu'il faut signaler comme telle.

Vérifier systématiquement qu'une décision ancienne n'a pas été abandonnée. Un fichage d'abandon de jurisprudence prime la solution ancienne.

Voir `references/hierarchie-jurisprudence-administrative.md`.

## 7. Structure de la décision

Visas, motifs, dispositif. Les mentions obligatoires figurent à l'article R. 741-2 du code de justice administrative : en récupérer le texte en vigueur avant de vérifier une décision.

Voir `references/structure-decision.md`.

## 8. Points de vigilance

À faire :

- Vérifier la compétence, la recevabilité et l'existence d'un litige avant le fond.
- Choisir la grille du contentieux en cause avant de qualifier les moyens.
- Traiter la légalité externe avant la légalité interne, sauf motif exprès de faire autrement.
- Traiter les questions préalables, dont les fins de non-recevoir, avant le fond.
- Communiquer tout moyen relevé d'office avant de s'en saisir.
- Récupérer le texte intégral de chaque article et de chaque motif cité.
- Indiquer le niveau de publication de chaque décision citée.
- Vérifier la version du texte applicable à la date pertinente.

À éviter :

- Transposer une règle de procédure civile.
- Fonder une solution de principe sur une décision inédite.
- Citer un texte dans sa version actuelle pour un litige régi par une version antérieure.
- Écrire un motif hypothétique ou dubitatif.
- Répondre aux arguments plutôt qu'aux moyens.
- Employer les catégories de légalité externe et interne en matière fiscale.
- Ranger la recevabilité de la réclamation préalable parmi les moyens de procédure d'imposition.
- Placer l'annulation du jugement du côté de l'intimé, ou traiter cette demande comme un moyen.
- Nommer une pièce ou une source autrement que par sa dénomination réelle.

## Fichiers de référence

Ces fichiers accompagnent la version publiée sur GitHub (dépôt `claude-skills`) ; le présent SKILL.md se suffit pour l'essentiel.

- `references/contentieux-fiscal.md`
- `references/office-du-juge-administratif.md`
- `references/conclusions-moyens-arguments.md`
- `references/syllogisme-et-motivation.md`
- `references/structure-decision.md`
- `references/hierarchie-jurisprudence-administrative.md`

## Origine

Ce skill est dérivé de `raisonnement-juridique` d'Amaury Fouret, publié sous licence MIT, qui porte sur le contentieux civil. En sont repris la règle du texte intégral avant citation, la distinction entre ce qui appelle une réponse du juge et ce qui n'en appelle pas, l'ossature du syllogisme et le principe d'une hiérarchie explicite des décisions. En sont écartés le code de procédure civile, la structure du jugement civil, la taxonomie de la Cour de cassation et la dépendance à des outils externes.
