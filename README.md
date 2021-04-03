# ML-Adverse-Pharmaceuticals-Events
Analyze RxNorm Data

Table of content
- [Task](#task)  
- [What is RxNorm](#what-is-rxnorm)  

## Task
I plan to get the data from RxNorm and analyze it. Then I will try to use some AI or ML on it.

Tasks

- [ ] What is RxNorm

## What is RxNorm
RxNorm is a name of a US-specific terminology in medicine that contains all medications available on US market.
 Source: [wiki](https://en.wikipedia.org/wiki/RxNorm)
 
 RxNorm provides normalized names for clinical drugs and links its names to many of the drug vocabularies 
 commonly used in pharmacy management and drug interaction software, including those of First Databank,
  Micromedex, and Gold Standard Drug Database. By providing links between these vocabularies,
   RxNorm can mediate messages between systems not using the same software and vocabulary. 
   Source: [Official RxNorm site](https://www.nlm.nih.gov/research/umls/rxnorm/index.html)

## Content
source: [kaggle](https://www.kaggle.com/nlm-nih/nlm-rxnorm)

RxNorm was created by the U.S. National Library of Medicine (NLM) to provide a normalized naming system for clinical drugs, defined as the combination of {ingredient + strength + dose form}. In addition to the naming system, the RxNorm dataset also provides structured information such as brand names, ingredients, drug classes, and so on, for each clinical drug. Typical uses of RxNorm include navigating between names and codes among different drug vocabularies and using information in RxNorm to assist with health information exchange/medication reconciliation, e-prescribing, drug analytics, formulary development, and other functions.

This public dataset includes multiple data files originally released in RxNorm Rich Release Format (RXNRRF) that are loaded into Bigquery tables. The data is updated and archived on a monthly basis.

The following tables are included in the RxNorm dataset:

- RXNCONSO contains concept and source information

- RXNREL contains information regarding relationships between entities

- RXNSAT contains attribute information

- RXNSTY contains semantic information

- RXNSAB contains source info

- RXNCUI contains retired rxcui codes

- RXNATOMARCHIVE contains archived data

- RXNCUICHANGES contains concept changes

Update Frequency: Monthly

Fork this kernel to get started with this dataset.