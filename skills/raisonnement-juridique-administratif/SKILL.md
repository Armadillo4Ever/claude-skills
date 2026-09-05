---
name: raisonnement-juridique-administratif
description: "Modélise le raisonnement du juge administratif français pour l'analyse d'un dossier et la rédaction d'une décision. À utiliser dès qu'il est question d'un recours pour excès de pouvoir, de plein contentieux ou d'un référé : analyser une requête, identifier les questions de droit, distinguer conclusions, moyens et arguments, apprécier si un moyen est opérant ou d'ordre public, construire le syllogisme, rédiger des motifs en style direct et un dispositif, ou peser l'autorité d'une décision du Conseil d'État. À utiliser aussi lorsque l'utilisateur ne dit ni « décision » ni « jugement », par exemple pour un projet de rapporteur, une note ou l'examen d'un mémoire. Ne pas l'utiliser pour le contentieux judiciaire."
metadata:
  author: "Armadillo4Ever"
  license: "mit"
  version: "2026-09-05"
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

Voir `references/conclusions-moyens-arguments.md`.

## 3. Office du juge administratif

Points structurants, développés dans `references/office-du-juge-administratif.md` :

- La motivation est obligatoire, article L. 9 du code de justice administrative.
- La procédure est inquisitoire : le juge dirige l'instruction, ordonne les mesures utiles et peut demander la production de pièces.
- Le juge relève d'office les moyens d'ordre public. Il en informe préalablement les parties et les invite à présenter leurs observations, article R. 611-7 du code de justice administrative. Omettre cette communication est une cause d'annulation.
- Le juge de l'excès de pouvoir peut se borner à retenir un moyen suffisant pour prononcer l'annulation. Cette économie de moyens connaît des limites, notamment lorsque l'examen d'un autre moyen commande les mesures d'exécution ou l'injonction sollicitée. Trancher ce point explicitement plutôt que par défaut.
- Le juge de plein contentieux se prononce sur la situation à la date de sa décision, le juge de l'excès de pouvoir apprécie en principe la légalité à la date de l'acte. Vérifier la règle propre au contentieux en cause avant de fixer la date d'appréciation.

## 4. Syllogisme et motivation

La motivation s'écrit en style direct, par paragraphes numérotés, à l'indicatif présent. Le « considérant que » est abandonné.

**Majeure.** Énoncer la règle applicable, texte et interprétation jurisprudentielle, dans sa version applicable au litige, en précisant les conditions d'application et le régime de la preuve.

**Mineure.** Appliquer aux faits établis par l'instruction, apprécier les pièces, répondre aux moyens, qualifier juridiquement.

**Conclusion.** Tirer la conséquence, en cohérence avec la majeure et la mineure, et la reprendre au dispositif.

Proscrire les motifs hypothétiques, dubitatifs ou surabondants. Un motif qui ne soutient aucune conclusion n'a pas sa place dans la décision.

Voir `references/syllogisme-et-motivation.md`.

## 5. Autorité des décisions

Deux échelles se combinent, la formation de jugement et le niveau de publication. Elles ne se substituent pas l'une à l'autre : une décision d'Assemblée publiée prime, une décision inédite d'une chambre ne fonde pas à elle seule une solution de principe.

Formations, par autorité décroissante : Assemblée du contentieux, Section du contentieux, chambres réunies, chambre jugeant seule, juge statuant seul et ordonnances.

Publication : publié au Recueil Lebon, mentionné aux tables, inédit. Dans les fonds internes, ces niveaux correspondent aux lettres A, B et C.

Les avis rendus sur demande d'une juridiction, article L. 113-1 du code de justice administrative, ont une autorité propre qu'il faut signaler comme telle.

Vérifier systématiquement qu'une décision ancienne n'a pas été abandonnée. Un fichage d'abandon de jurisprudence prime la solution ancienne.

Voir `references/hierarchie-jurisprudence-administrative.md`.

## 6. Structure de la décision

Visas, motifs, dispositif. Les mentions obligatoires figurent à l'article R. 741-2 du code de justice administrative : en récupérer le texte en vigueur avant de vérifier une décision.

Voir `references/structure-decision.md`.

## 7. Points de vigilance

À faire :

- Vérifier la compétence, la recevabilité et l'existence d'un litige avant le fond.
- Traiter la légalité externe avant la légalité interne, sauf motif exprès de faire autrement.
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
- Nommer une pièce ou une source autrement que par sa dénomination réelle.

## Fichiers de référence

- `references/office-du-juge-administratif.md`
- `references/conclusions-moyens-arguments.md`
- `references/syllogisme-et-motivation.md`
- `references/structure-decision.md`
- `references/hierarchie-jurisprudence-administrative.md`

## Origine

Ce skill est dérivé de `raisonnement-juridique` d'Amaury Fouret, publié sous licence MIT, qui porte sur le contentieux civil. En sont repris la règle du texte intégral avant citation, la distinction entre ce qui appelle une réponse du juge et ce qui n'en appelle pas, l'ossature du syllogisme et le principe d'une hiérarchie explicite des décisions. En sont écartés le code de procédure civile, la structure du jugement civil, la taxonomie de la Cour de cassation et la dépendance à des outils externes.
