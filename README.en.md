# claude-skills

Skills for Claude, written for legal work and for building drafting-assistance tools in French administrative law.

The English files (`*.en.md`) are twins of the French files; in case of discrepancy, the French text prevails.

## Contents

| Skill | Purpose |
|---|---|
| [`raisonnement-juridique-administratif`](skills/raisonnement-juridique-administratif) | Reasoning of the administrative judge: analysis of the case file, claims, pleas and arguments, preliminary questions, the grid specific to each type of litigation (excess of power, tax, liability, appeal, cassation), the judge's office, syllogism and statement of grounds, authority of decisions, structure of the decision. With a reference file on tax litigation, articles verified on Légifrance. |
| [`identification-des-moyens-contentieux-administratif`](skills/identification-des-moyens-contentieux-administratif) | Identify the claims, pleas and preliminary questions of a litigation case file from the written submissions: taxonomy of pleas by type of litigation, anchoring of each plea on a quoted passage of the submission and mechanical check of the quotation, safeguards, order of examination, examination of the court's own motion on a closed list, public-policy pleas, measurements drawn from the open data of the administrative courts (one million decisions). |
| [`ordonnances-juridictionnelles-contentieux-administratif`](skills/ordonnances-juridictionnelles-contentieux-administratif) | Draft an order (*ordonnance*) of an administrative tribunal, administrative court of appeal or the Conseil d'État: every case (withdrawal, incompetence, no need to adjudicate, inadmissibility, series, manifestly unfounded pleas, manifestly unfounded appeal, non-admission of cassation appeals, interim relief, jurisdiction, investigation, enforcement), the text in force of each legal basis in the Code of Administrative Justice, what the grounds must establish, the formal layout specific to each level of court, the signals to look for in a case file and the checks before signature; frequencies observed in open data. English twin in progress. |
| [`note-de-contentieux-administratif`](skills/note-de-contentieux-administratif) | Draft the rapporteur's litigation note (administrative tribunal, administrative court of appeal, Conseil d'État) from a case file: headings and organisation, documents to read first, method of analysis of each preliminary question (withdrawal, incompetence, no need to adjudicate, inadmissibilities) with the document, the text, its application and the question of regularisation, standard organisation of the answer to a plea as a syllogism, standard plans and reasoning in excess of power, liability and tax litigation, appeal and cassation, ancillary claims and operative part. English twin in progress. |
| [`examen-consultatif-projet-de-texte`](skills/examen-consultatif-projet-de-texte) | Legal review of a draft normative text, in the advisory order: competence, legal basis, consultations, constitutionality, compatibility with international commitments, articulation with existing law, legislative drafting, overseas territories, entry into force. |
| [`legistique-modifications-de-textes`](skills/legistique-modifications-de-textes) | Read, apply and draft the instructions by which one text amends another; counting of paragraphs, compound designations, consolidation, three-column table. |
| [`tableau-trois-colonnes`](skills/tableau-trois-colonnes) | Build, check or correct the three-column table (law in force, draft text, consolidated text) of a draft text: designate without copying, distinguish the anchor from the target, one row per operation, column 3 always filled, incidents reported rather than applied by guesswork. |
| [`relecture-legistique`](skills/relecture-legistique) | Proofreading of the form of a draft text against the entries of the Legislative Drafting Guide: language, tense and mood, acronyms, legal terms, articles and paragraphs, punctuation, typography of the Official Journal, recitals, cross-references. Output as a table of deviations, each grounded in an entry of the Guide. |

The skills complement one another: the advisory review deals with the substance of the draft and calls on the legislative drafting of amendments to read an amending text; the three-column table gives an account of it, article by article, and serves as the basis for the review; the legislative proofreading deals with form only; administrative reasoning applies to litigation and does not transpose to advisory work; the identification of pleas is its first step, the one that establishes what the case file contains before any reasoning; the litigation note comes next, examining the preliminary questions document by document and building the answer to each plea; orders are its short outcome, when the file calls for neither investigation nor hearing.

## Installation

Copy the skill folder into the skills directory of your Claude environment, or take its content into an account skill. The `SKILL.md` file is sufficient on its own; the `references/` files add depth when the environment loads them.

## Disclaimer

These skills are tools to assist analysis and drafting. They do not dispense with any verification, and court decisions as well as opinions are the sole responsibility of those who render them. They are a personal work and do not commit any institution.

## Licence

MIT, © Armadillo4Ever. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md) for attributions.
