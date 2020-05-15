# Efavirenz-Model
Whole-body PBPK model of efavirenz as CYP3A4 perpetrator drug 

<a title="Yikrazuul / Public domain" href="https://commons.wikimedia.org/wiki/File:Efavirenz.png"><img width="512" alt="Efavirenz" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/Efavirenz.png/512px-Efavirenz.png"></a>



This repository contains:

- a PK-Sim snapshot (*.json) file of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](../../releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**



This efavirenz model is intended to be used as perpetrator drug in CYP3A4-mediated drug-drug interactions (DDI). 

This  whole-body PBPK model of efavirenz has been developed using in particular published pharmacokinetic clinical data by Ogburn *et al.* 2010 [[1](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)], Mouly *et al.* 1999 [[2](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)], Xu *et al.* 2013 [[3](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)], Dooley *et al.* 2012 [[4](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)] , Garg et al. 2013 [[5](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)] and Huang *et al.* 2012 [[6](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)]. For the parameterization of CYP3A4 interaction, concentration-time profiles of efavirenz-midazolam interaction studies of Mikus *et al.* 2017  [[7](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)] and Katzenmaier *et al.* 2010 [[8](https://github.com/Open-Systems-Pharmacology/Efavirenz-Model#references)] were used. 

Within this repository, we distribute a whole-body PBPK model of efavirenz, that has been carefully developed using a large number of clinical studies and evaluated within our DDI modeling network. 

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License

The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References

[1] [Ogburn ET, Jones DR, Masters AR, Xu C, Guo Y, Desta Z. Efavirenz primary and secondary metabolism in vitro and in vivo: identification of novel metabolic pathways and cytochrome P450 2A6 as the principal catalyst of efavirenz 7-hydroxylation. Drug Metab Dispos. 2010 Jul;38(7):1218-29. doi: 10.1124/dmd.109.031393. Epub 2010 Mar 24. PubMed PMID: 20335270; PubMed Central PMCID: PMC2908985.](https://www.ncbi.nlm.nih.gov/pubmed/20335270)

[2] [Mouly S, Lown KS, Kornhauser D, Joseph JL, Fiske WD, Benedek IH, Watkins PB. Hepatic but not intestinal CYP3A4 displays dose-dependent induction by efavirenz in humans. Clin Pharmacol Ther. 2002 Jul;72(1):1-9. PubMed PMID: 12151999.](https://www.ncbi.nlm.nih.gov/pubmed/12151999)

[3] [Xu C, Quinney SK, Guo Y, Hall SD, Li L, Desta Z. CYP2B6 pharmacogenetics-based in vitro-in vivo extrapolation of efavirenz clearance by physiologically based pharmacokinetic modeling. Drug Metab Dispos. 2013 Dec;41(12):2004-11. doi: 10.1124/dmd.113.051755. Epub 2013 Jul 11. PubMed PMID: 23846872; PubMed Central PMCID: PMC3834132.](https://www.ncbi.nlm.nih.gov/pubmed/23846872)

[4] [Dooley KE, Park JG, Swindells S, Allen R, Haas DW, Cramer Y, Aweeka F, Wiggins I, Gupta A, Lizak P, Qasba S, van Heeswijk R, Flexner C; ACTG 5267 Study Team. Safety, tolerability, and pharmacokinetic interactions of the antituberculous agent TMC207 (bedaquiline) with efavirenz in healthy volunteers: AIDS Clinical Trials Group Study A5267. J Acquir Immune Defic Syndr. 2012 Apr 15;59(5):455-62. doi: 10.1097/QAI.0b013e3182410503. PubMed PMID: 22126739; PubMed Central PMCID: PMC3302922.](https://www.ncbi.nlm.nih.gov/pubmed/22126739)

[5] [Garg V, Chandorkar G, Yang Y, Adda N, McNair L, Alves K, Smith F, van Heeswijk RP. The effect of CYP3A inhibitors and inducers on the pharmacokinetics of telaprevir in healthy volunteers. Br J Clin Pharmacol. 2013 Feb;75(2):431-9. doi: 10.1111/j.1365-2125.2012.04345.x. PubMed PMID: 22642697; PubMed Central PMCID: PMC3579258.](https://www.ncbi.nlm.nih.gov/pubmed/22642697)

[6] [Huang L, Parikh S, Rosenthal PJ, Lizak P, Marzan F, Dorsey G, Havlir D, Aweeka FT. Concomitant efavirenz reduces pharmacokinetic exposure to the antimalarial drug artemether-lumefantrine in healthy volunteers. J Acquir Immune Defic Syndr. 2012 Nov 1;61(3):310-6. doi: 10.1097/QAI.0b013e31826ebb5c. PubMed PMID: 22918158; PubMed Central PMCID: PMC3511816.](https://www.ncbi.nlm.nih.gov/pubmed/22918158)

[7] [Mikus G, Heinrich T, Bödigheimer J, Röder C, Matthee AK, Weiss J, Burhenne J, Haefeli WE. Semisimultaneous Midazolam Administration to Evaluate the Time Course of CYP3A Activation by a Single Oral Dose of Efavirenz. J Clin Pharmacol. 2017 Jul;57(7):899-905. doi: 10.1002/jcph.879. Epub 2017 Feb 14. PubMed PMID: 28194792.](https://www.ncbi.nlm.nih.gov/pubmed/28194792)

[8] [Katzenmaier S, Markert C, Mikus G. Proposal of a new limited sampling strategy to predict CYP3A activity using a partial AUC of midazolam. Eur J Clin Pharmacol. 2010 Nov;66(11):1137-41. doi: 10.1007/s00228-010-0878-2. Epub 2010 Aug 3. PubMed PMID: 20680253.](https://www.ncbi.nlm.nih.gov/pubmed/20680253)