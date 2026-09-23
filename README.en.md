# claude-skills

Skills for Claude, written for legal work and for building drafting-assistance tools in French administrative law.

The English files (`*.en.md`) are twins of the French files; in case of discrepancy, the French text prevails.

## Contents

| Skill | Purpose |
|---|---|
| [`raisonnement-juridique-administratif`](skills/raisonnement-juridique-administratif) | Reasoning of the administrative judge: analysis of the case file, claims, pleas and arguments, preliminary questions, the grid specific to each type of litigation (excess of power, tax, liability, appeal, cassation), the judge's office, syllogism and statement of grounds, authority of decisions, structure of the decision. With a reference file on tax litigation, articles verified on Légifrance. |
| [`examen-consultatif-projet-de-texte`](skills/examen-consultatif-projet-de-texte) | Legal review of a draft normative text, in the advisory order: competence, legal basis, consultations, constitutionality, compatibility with international commitments, articulation with existing law, legislative drafting, overseas territories, entry into force. |
| [`legistique-modifications-de-textes`](skills/legistique-modifications-de-textes) | Read, apply and draft the instructions by which one text amends another; counting of paragraphs, compound designations, consolidation, three-column table. |
| [`tableau-trois-colonnes`](skills/tableau-trois-colonnes) | Build, check or correct the three-column table (law in force, draft text, consolidated text) of a draft text: designate without copying, distinguish the anchor from the target, one row per operation, column 3 always filled, incidents reported rather than applied by guesswork. |
| [`relecture-legistique`](skills/relecture-legistique) | Proofreading of the form of a draft text against the entries of the Legislative Drafting Guide: language, tense and mood, acronyms, legal terms, articles and paragraphs, punctuation, typography of the Official Journal, recitals, cross-references. Output as a table of deviations, each grounded in an entry of the Guide. |

The five skills complement one another: the advisory review deals with the substance of the draft and calls on the legislative drafting of amendments to read an amending text; the three-column table gives an account of it, article by article, and serves as the basis for the review; the legislative proofreading deals with form only; administrative reasoning applies to litigation and does not transpose to advisory work.

## Installation

Copy the skill folder into the skills directory of your Claude environment, or take its content into an account skill. The `SKILL.md` file is sufficient on its own; the `references/` files add depth when the environment loads them.

## Disclaimer

These skills are tools to assist analysis and drafting. They do not dispense with any verification, and court decisions as well as opinions are the sole responsibility of those who render them. They are a personal work and do not commit any institution.

## Licence

MIT. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md) for attributions.
