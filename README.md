# ML-Adverse Pharmaceuticals Events
Analyze Adverse Pharmaceuticals Events

Table of content
- [Task](#task)  
- [Keggle](#keggle)  

## Task
Find which drugs cause Advers Pharmaceutical events
Still need to be determent more exactly

Tasks

- [ ] Where is data
- [ ] How to access data
- [ ] Exploratory Data analysis (Check what can I predict, where ML can be used)

## Keggle
sorce: https://www.kaggle.com/fda/adverse-pharmaceuticals-events

### Context:
Identification of adverse drug reactions (ADRs) during the post-marketing phase is one of the most important goals of drug safety surveillance. Spontaneous reporting systems (SRS) data, which are the mainstay of traditional drug safety surveillance, are used for hypothesis generation and to validate the newer approaches. The publicly available US Food and Drug Administration (FDA) Adverse Event Reporting System (FAERS) data requires substantial curation before they can be used appropriately, and applying different strategies for data cleaning and normalization can have material impact on analysis results.

### Content:
We provide a curated and standardized version of FAERS removing duplicate case records, applying standardized vocabularies with drug names mapped to RxNorm concepts and outcomes mapped to SNOMED-CT concepts, and pre-computed summary statistics about drug-outcome relationships for general consumption. This publicly available resource, along with the source code, will accelerate drug safety research by reducing the amount of time spent performing data management on the source FAERS reports, improving the quality of the underlying data, and enabling standardized analyses using common vocabularies.

### Acknowledgements:
Data available from [this source](http://datadryad.org/resource/doi:10.5061/dryad.8q0s4).

When using this data, please cite the original publication:

Banda JM, Evans L, Vanguri RS, Tatonetti NP, Ryan PB, Shah NH (2016) A curated and standardized adverse drug event resource to accelerate drug safety research. Scientific Data 3: 160026. http://dx.doi.org/10.1038/sdata.2016.26

Additionally, please cite the Dryad data package:

Banda JM, Evans L, Vanguri RS, Tatonetti NP, Ryan PB, Shah NH (2016) Data from: A curated and standardized adverse drug event resource to accelerate drug safety research. Dryad Digital Repository. http://dx.doi.org/10.5061/dryad.8q0s4

### Inspiration:
This is a large-ish dataset (~4.5 gb uncompressed), so try out your batch processing skills in a Kernel
What groups of drugs are most risky?
What medical conditions are most at risk to drug-associated risks?

## Data access

Data can be accessed [here](https://datadryad.org/stash/dataset/doi:10.5061/dryad.8q0s4) as it said on kaggle.
The data is from 2017. 


# TO DO
- [ ] Read the article of this data https://datadryad.org/stash/dataset/doi:10.5061/dryad.8q0s4
- [ ] Check [FAERS](https://open.fda.gov/data/faers/#:~:text=About%20FAERS-,The%20FDA%20Adverse%20Event%20Reporting%20System%20(FAERS)%20is%20a%20database,drug%20and%20therapeutic%20biologic%20products.)
official site for new version of data