---
name: "identification-des-moyens-contentieux-administratif"
description: "Identify the claims, pleas and preliminary questions of a French administrative litigation case file (TA, CAA, Conseil d'État) from the written submissions: taxonomy of pleas by type of litigation, anchoring of each plea on a passage of the submission, safeguards, order of examination, public-policy pleas, measurements drawn from open data."
---

# Identifying pleas in French administrative litigation

English twin of `SKILL.md`; in case of discrepancy, the French text prevails. "Plea" translates *moyen*, "claim" translates *conclusions*, "preliminary question" translates *question préalable*.

Method established between August and October 2026 for the ALCEJA and KIARA demonstrators, from public data only: the open data of administrative court decisions (opendata.justice-administrative.fr, 940,166 decisions of administrative tribunals, 114,338 of administrative courts of appeal, 38,799 of the Conseil d'État, read in August 2026), the case files of the direct recruitment competition for administrative tribunal and court of appeal judges (litigation case-file test, 2017 to 2026), the Code of Administrative Justice (CJA, Légifrance) and published case law. No real case content, no internal note, no fact of a specific case appears here. The figures quoted are measurements on those data; they describe an observed practice, never a rule of law.

## 1. The object: what a plea is, and what it is not

A plea is a criticism that calls for its own answer from the judge. It differs from three things that look like it and with which any automatic extraction confuses it:

- the claim, which is what the party asks for (annulment, discharge, award of a sum, injunction, penalty payment, costs under article L. 761-1); asking for the annulment of the judgment is not a plea, it is a claim;
- the argument, which supports a plea without legal effect of its own: an example, an exhibit, a figure, a calculation, a cited precedent; the judge does not answer it;
- the preliminary question, dealt with before the merits and not of the nature of a plea: withdrawal, jurisdiction of the court, no need to adjudicate, admissibility (time limit, interest, standing, prior decision, new claims), objections of inadmissibility raised by the defendant.

The level of the extraction is the one the judge distinguishes in the grounds: a plea is a question of law, whose branches and arguments are gathered in its statement. Two criticisms each calling for a distinct answer are two pleas, even under the same heading, even against the same act. The same plea repeated from one submission to the next counts once, in its most complete wording.

The rule of proportion, measured on six competition case files in September 2026: submissions read in full yield 2 to 176 raw criticisms per file, the decision rendered distinguishes 1 to 18. An extraction exceeding twenty-five pleas has gone down to the level of the argument; it must regroup, never discard a distinct criticism.

## 2. The anchoring rule, which prevails over everything

A plea is written only if it is drawn from an identified passage of the submission. For each plea, the extraction carries the document (application, defence, reply, rejoinder, appeal brief, cassation appeal), the page, and an exact short quotation (thirty words at most, copied word for word, OCR errors included) of the passage that articulates the criticism. A plea without an identified passage is not a plea of the case file: it is reported separately, under the mention "plea not articulated, to be checked", never entered in the list.

The reason is precise and verified: a well-formed plea is more convincing, including when it is wrong. The patterns observed in open data (section 6) give the form of the plea; they never give its content. The rule breached, what the court decided and why it would be an error come from the case file and from it alone. Never fill a mould with what one believes to know of the law.

The quotation is then checked mechanically, without judgment: does the cited page contain the passage? Statuses used: "established" (passage found on the stated page, above 0.82 window similarity; "literal" if identical), "wrong page" (found elsewhere, page indicated), "not found", "no page", "no quotation" (fewer than fifteen useful characters), and "discordant figures": above the threshold, every number of the quotation, in digits or in words, and every month name must appear on the page, otherwise the plea is not established. A lateness "for failure to be registered within the three-month period", when the submission says "two months", is not established. Nothing is removed from the extraction: a plea not found is kept and flagged, because it may be a real plea badly cited (noisy OCR, paraphrase) or an invented plea, and only the reader can decide.

## 3. First determine the type of litigation

The extraction changes grid according to the type of litigation, to be fixed first, on reading the claims:

- excess of power (*excès de pouvoir*) and objective full jurisdiction: the pleas are pleas of legality, divided between external legality and internal legality;
- tax full jurisdiction (the applicant seeks the discharge or reduction of a tax or penalties): the plan is, on appeal, the regularity of the judgment, then the pleas on the taxation procedure, then the merits, then the penalties; never use "external / internal legality" in tax matters;
- compensation full jurisdiction: the points of liability, namely the generating fact (fault or no-fault liability), the causal link, each head of damage with its assessment;
- cassation: pleas on the regularity of the contested decision (composition, statement of grounds, procedure) and pleas on the merits (error of law, distortion, error in the legal characterisation of facts, misconstruction by the judge of his office).

When the contested act is a judgment or a ruling, criticisms of the formal regularity of that decision (insufficient or missing grounds, failure to rule, contradictory grounds, irregular composition or procedure) form a "regularity of the judgment" branch, placed first. Challenging the merits of the solution adopted is not part of it.

## 4. Taxonomy of pleas

### 4.1 Excess of power and objective full jurisdiction

External legality: lack of competence of the author of the act (material, territorial, temporal, lack of delegation, negative incompetence); procedural defect (mandatory consultation omitted or irregular, prior adversarial procedure, public inquiry, urgency procedure, opinion not obtained) with, for each, the question of its effect on the meaning of the decision or on a guarantee (Danthony case law, CE, ass., 23 December 2011, no. 335033); formal defect (missing or insufficient statement of reasons, missing signature, mandatory mentions).

Internal legality: error of law (inapplicable text, breach of a text or principle, plea of illegality of the regulation applied, scope of the law); error of fact (material inaccuracy); error in the legal characterisation of facts; error of assessment according to the intensity of review (normal review, review restricted to manifest error, balance, proportionality); misuse of power or procedure, retained in the alternative.

Pleas of external legality are the most often missed by a quick reading, because submissions articulate them in a few lines before developing the merits. Look for them expressly.

### 4.2 Tax full jurisdiction

Taxation procedure: only the regularity of the audit and of the adjustment (taxpayer guarantees, oral and adversarial debate, reasons of the adjustment proposal, taxpayer charter, limitation of the right of recovery, fairness). Merits: base, rate, application of the tax law, characterisation of income, allowances, applicable regime. Penalties: basis, reasons, proportion, good faith.

Measured trap: the admissibility of the prior claim or of the application (time limit of article R. 196-1 of the Book of Tax Procedures, existence of a claim, proof of its dispatch, credit position) is not a procedural plea, it is a preliminary question of admissibility, whether raised by the applicant or opposed by the administration. Another rule specific to the matter: the inadmissibility of pleas based on a new legal cause (section 8) does not apply to tax base litigation (Book of Tax Procedures, art. L. 199 C).

### 4.3 Compensation full jurisdiction

Liability regime (fault, risk, lack of normal maintenance, breach of equality before public burdens, ten-year guarantee, contractual liability); liable person and attributability; damaging fact and its characterisation; existence and extent of each head of damage; direct and certain causal link, loss of chance; exonerating causes (victim's fault, act of a third party, force majeure); assessment and date of assessment; interest and capitalisation; rights of social security funds. The defects proper to the decision that bound the dispute have no bearing on the solution (CE, 11 June 2003, no. 248865): a "plea" invoking them is ineffective and is flagged as such. Four-year limitation (Law no. 68-1250 of 31 December 1968) is examined only if the administration has raised it.

### 4.4 Appeal

The extraction carries two series: the pleas directed against the judgment (regularity: composition, grounds, failure to rule, procedure; then merits, that is the criticism of the solution) and the pleas directed against the initial act, repeated from first instance or new. An appeal that repeats the first-instance pleas without criticising the judgment is a signal for the order rejecting a manifestly unfounded appeal (R. 222-1, last paragraph). Roles are reversed compared with instinct: the appellant is the party seising the court and seeking the annulment or reversal of the judgment, even when it is the administration; its claims go on the applicant's side; the respondent concludes to rejection. Never place the annulment of the judgment on the defendant's side.

### 4.5 Cassation

The grievances of the appeal in cassation are the pleas of cassation: error of law, distortion of the documents in the file, insufficient grounds, inaccurate legal characterisation of facts, contradictory grounds, misconstruction by the judge of his office, misreading of the submissions, irregularity of the contested decision. A plea amounting to challenging the sovereign assessment of facts by the trial judges is inadmissible in cassation: identify it and qualify it so. The applicant in cassation is the one from whom the pleas emanate; the party concluding to rejection is never the applicant.

### 4.6 What open data shows of the frequency of pleas

Most used categories of pleas, after neutralisation of case-specific variables (count on the formulas "il soutient que", "le moyen tiré de", August 2026):

- administrative tribunals (916,348 decisions read): error of law, procedural defect, manifest error of assessment, error of fact, error of assessment, inadmissibility of the application (raised in defence), formal defect, misuse of power, lack of legal basis, lack of reasons, breach of res judicata, incompetence; in interim relief, urgency and serious doubt, usefulness of the measure;
- administrative courts of appeal (114,338): error of law, irregularity of the judgment, error of fact, manifest error of assessment, procedural defect, insufficient reasons of the judgment, incompetence of the signatory, failure to rule, material error;
- Conseil d'État (35,350): error of law (6,242 occurrences), distortion of the documents in the file (4,158), insufficient grounds (2,153), inaccurate legal characterisation of facts (806), irregularity (781), contradictory grounds, misconstruction by the judge of his office, misreading of the submissions, breach of the adversarial principle.

Two lessons of this measurement. First, 245 distinct categories in tribunals, 222 in courts of appeal, 264 at the Conseil d'État: the taxonomy of section 4 covers the essential, but the extraction keeps the terms of the submission and never forces a criticism into a category. Second, every distillation error produced plausible and false results (625 false pleas born of an "en ce qui", 1,926 occurrences of a non-existent plea drawn from a hyphen): the abundance of a result is never an indication of its accuracy; it is checked against the source.

## 5. Preliminary questions: extract them separately, and look for them of the court's own motion

They are ranked in the judge's invariable order of examination (withdrawal, incompetence, no need to adjudicate, inadmissibilities, then the merits):

1. withdrawal, express or deemed (announced supplementary brief not produced: R. 612-5 in tribunals and courts, R. 611-22 at the Conseil d'État; maintenance of the application not confirmed after invitation: R. 612-5-1); withdrawal prevails over jurisdiction;
2. jurisdiction of the administrative courts (public-policy plea), then jurisdiction within the administrative order (material, territorial, first and last instance, referral, connexity); territorial incompetence not invoked before the closing of the investigation at first instance can no longer be raised on appeal;
3. no need to adjudicate: withdrawal or repeal of the act become final, satisfaction given, tax relief, disappearance of the object; on appeal, the no need to adjudicate is pronounced even if the appeal is inadmissible;
4. admissibility: contested decision (act open to challenge, internal measure, preparatory act, confirmatory act, soft law), notification or publication, mention of remedies and time limits (R. 421-5), time limit and starting point (R. 421-1; reasonable one-year period absent such mention: CE, ass., 13 July 2016, Czabaj, no. 387763), prior administrative appeal, prior decision binding the dispute (R. 421-1, 2nd paragraph), mandatory prior mediation or administrative appeal, standing and interest, authorisation of the legal person, representation (R. 431-2 and R. 431-3), new claims, unquantified claims;
5. curable inadmissibilities: the judge cannot oppose them without having invited regularisation (R. 612-1); check whether the invitation is in the file and remained unanswered.

For each question, the extraction states who raised it (the applicant, the defendant, nobody) and what the file says of it. Objections of inadmissibility by the defendant are the most often missed: treat as such any mention, in the defence, of an application or claims described as inadmissible or of a challenge become devoid of object, even under spelling corrupted by OCR.

An examination of the court's own motion, on a closed list, follows the extraction: each item of the list is reviewed, stated "raised", "to be examined of the court's own motion" or "not applicable", with the reference to document and page. Measurement of 12 September 2026 on a competition file: the closed list retains 11 questions out of 19 against 6 for an open instruction. An item retained without reference in the file is flagged, never asserted.

## 6. What is extracted together with the pleas

An extraction usable by the judge carries, besides the pleas, the following elements, each with its page: type of litigation; subject matter (tax, foreigners, civil service, planning, hospital liability, environment, contracts, etc.); court seised; applicant and defendant, in their exact roles; contested act and its date; object of the dispute in one sentence; texts relied on by the parties (code and article); exhibits produced; claims of each party, submission by submission, with new claims flagged; preliminary questions; procedural dates (decision, notification, administrative appeal, registration, judgment). The applicant's pleas and claims come from the application and replies; the defendant's claims and objections of inadmissibility, from the defence.

For long files, a sheet per document, drawn up on the full text in labelled forty-page slices, precedes consolidation: each sheet carries claims, pleas with branch, argument in three sentences, pages and quotation, alleged facts, exhibits relied on, procedural dates, procedural questions. Consolidation merges the sheets into a list of at most twenty-five pleas, ranked in the order of examination, each plea keeping document, page and quotation. Measurement of 12 September 2026 (six files, 15 to 3,330 pages): full reading raises coverage of the pleas retained by the decision from 19 of 39 to 23 of 39 and removes surplus pleas on small files; on the two largest, coverage plateaus not because of reading but because of the list, which must merge the sheets' pleas with those of the first reading.

## 7. Safeguards, applied to every extraction

Each answers an error observed on a real file; they apply in this order, after extraction and before any use:

1. tax grid: in tax matters, the branches are "taxation procedure" and "merits" (and "regularity of the judgment" on appeal); any "external / internal legality" branch is reclassified;
2. request for annulment or reversal of the judgment: removed from the pleas, unless it carries a regularity criticism, in which case it becomes that plea;
3. admissibility of the tax claim: moved from procedural pleas to preliminary questions;
4. claim for annulment of the judgment placed on the defendant's side: returned to the appellant;
5. reversed roles (the party concluding to rejection entered as applicant): restored;
6. public authority "condemned" by its own claims: made defendant;
7. defendant without extracted claims: "rejection" claim added, marked to be confirmed;
8. order of examination imposed by rule, not by the model: admissibility, regularity of the judgment, external legality or procedure or liability, internal legality or merits or causation, penalties or damage, other; at equal rank, the order of the extraction.

Nothing is invented by consolidation: it receives the list, ranks it, checks it, and every plea returned must appear in what was given to it.

## 8. Admissibility and effectiveness of pleas, to be qualified at extraction

For each plea, say whether it calls for an answer on the merits or is set aside before:

- plea inadmissible as based on a new legal cause, invoked after the expiry of the time limit for the application (external legality versus internal legality: CE, sect., 20 February 1953, Société Intercopie, no. 9772); without effect in tax base litigation; without effect for a public-policy plea;
- new plea after the crystallisation date fixed by the judge (R. 611-7-1);
- ineffective plea: without bearing on the solution, for instance because the administration was in a situation of bound competence, or because it criticises the defects proper to the decision binding a compensation dispute;
- imprecise plea, not accompanied by the particulars allowing its merits to be assessed, or accompanied by facts manifestly unable to support it;
- in cassation, plea amounting to challenging the sovereign assessment of the trial judges, or plea new in cassation outside public policy.

This qualification commands two things: the plan of the note, and the possibility of an order of rejection under 7° of article R. 222-1 or of article R. 122-12, or of a non-admission (R. 822-5, 4°), when the application contains only pleas of that kind (see the orders skill).

## 9. Public-policy pleas, to be sought even if nobody raises them

The extraction reports, separately and with the reference that gives rise to them, the pleas the judge must raise of his own motion, after informing the parties (R. 611-7): incompetence of the author of the act, "the public-policy plea par excellence" (CE, 6 July 1973, Veyret, no. 79752); breach of the scope of the law (CE, sect., 21 March 1958, Delteil); absolute authority of res judicata; prohibition on ordering a public entity to pay a sum it does not owe (CE, 19 March 1971, no. 79962); consequences of a declaration of unconstitutionality; unlawful retroactivity (CE, ass., 25 June 1948, Société du journal L'Aurore). On appeal, the regularity of the judgment on certain points (competence of the first judge, admissibility of the first-instance application) is examined of the court's own motion. A public-policy plea is distinguished from the pleas raised by an explicit mention; it is not invented: it arises from a fact of the file (a signature without delegation in the file, a date placing the act outside the scope of the text), which is cited.

## 10. From the plea to the answer: what the measurement established

The distillation of open data (count of identical sentences after neutralisation of case-specific variables) established that the major premise repeats and the minor premise does not: only 10 % of grounds paragraphs recur twenty times or more. There is therefore no "model paragraph" per plea. Only three families of answers can be drafted from a pattern: rejection by way of consequence, finding on the very terms of the act, chain of delegation of competence (and that one is not copied: 1,198 occurrences, 1,051 distinct forms; its useful object is the ordered grid of points to check). The Conseil d'État level, ruling in cassation, feeds no pattern on the merits. All the rest of the answer comes from the file and the sources, plea by plea.

The consecrated formulas for naming a plea in the note or the decision: "le moyen tiré de ce que" followed by the criticism in the terms of the submission; "il soutient que" for the analysis of the pleadings; "le moyen tiré de la méconnaissance de l'article"; on appeal, "M. X relève appel du jugement par lequel" then "il soutient que le jugement est irrégulier en ce que"; in cassation, "il soutient que l'arrêt attaqué est entaché d'erreur de droit en ce que".

## 11. The extraction, in practice

Sequence, whatever the size of the file:

1. Read the inventory and the procedural documents in the order of the investigation; identify the parties, the roles, the contested act, the court, the type of litigation, the subject matter.
2. Extract, document by document, the claims; flag new claims and alternative claims.
3. Extract the pleas, document by document, at the level of the criticism, with branch, qualification, one-sentence statement faithful to the submission, pages, exact quotation, source document.
4. Extract the preliminary questions, those the parties raise and those the closed list of section 5 has examined of the court's own motion; extract the procedural dates that govern them.
5. Consolidate: deduplicate by heading and quotation, regroup at the level of the plea, ceiling of twenty-five flagged and not applied by cutting, order of examination imposed.
6. Check the anchoring of each plea (section 2) and qualify admissibility and effectiveness (section 8).
7. Report public-policy pleas (section 9) and unarticulated pleas.
8. Deliver the extraction in the requested form, with, for each line, what lets the reader check in one click: document, page, quotation.

Always, at the head of the extraction, the number of pleas, the number of pages read and, if applicable, the warning that the submitted text was truncated. An unverifiable plea costs the rapporteur more than it brings.

## 12. Checklist

- The type of litigation is fixed and the corresponding grid applied.
- No claim is entered as a plea; no preliminary question is entered as a plea.
- Each plea carries document, page and exact quotation; pleas not found are flagged, not removed; the figures of the quotation appear on the page.
- The defendant's objections of inadmissibility are extracted.
- Pleas of external legality have been expressly sought.
- The roles of the parties are exact on appeal and in cassation.
- The list is in the order of examination and does not exceed twenty-five pleas without saying so.
- Public-policy pleas and unarticulated pleas are reported separately.
- No em dash.

## Texts and decisions cited (checked on Légifrance, version in force on 9 September 2026)

Code of Administrative Justice: [R. 421-1](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000039807005); [R. 421-5](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000006449946); [R. 431-2](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000033340889); [R. 431-3](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000050760054); [R. 611-7](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000038114788); [R. 611-7-1](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000038114803); [R. 611-22](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000006450077); [R. 612-1](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000006450091); [R. 612-5](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000006450101); [R. 612-5-1](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000038117505); [R. 122-12](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000033340817); [R. 222-1](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000048830877); [R. 822-5](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000049919592); [L. 761-1](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000044570095).

Case law (references to be confirmed on ArianeWeb before citation in a decision): CE, sect., 20 February 1953, Société Intercopie, no. 9772; CE, sect., 21 March 1958, Delteil; CE, 6 July 1973, Veyret, no. 79752; CE, 19 March 1971, no. 79962; CE, ass., 25 June 1948, Société du journal L'Aurore; CE, 11 June 2003, no. 248865; CE, ass., 23 December 2011, Danthony, no. 335033; CE, ass., 13 July 2016, Czabaj, no. 387763.

Data: open data of administrative court decisions, https://opendata.justice-administrative.fr (open licence); subjects of the direct recruitment competition for TA and CAA judges, https://www.conseil-etat.fr.
