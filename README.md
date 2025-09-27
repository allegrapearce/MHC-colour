## Interpreting relationships among MHC, parasites, and secondary sexual colouration in a natural system

### Abstract
Differences in guppy (Poecilia reticulata) colour patterns can be driven by opposing selection pressures of predation and female mate choice, but the effect of parasitism has received less attention. We sought to test the Hamilton-Zuk hypothesis, which posits that immunocompetence can be selected for through sexual selection on ornamentations acting as honest signals of fitness. By studying 21 wild guppy populations in Trinidad, we analyzed relationships among parasitic infections by Gyrodactylus, male sexual ornamentation (colouration), and genetic variation at the Major Histocompatibility Complex (MHC) at both individual and population levels. We found population level support for a correlation between MHC functional supertype diversity and Gyrodactylus prevalence, as well as particular MHC supertypes that were correlated with Gyrodactylus prevalence. However, these relationships were not supported at the individual level. Further, much of this variation was explained by processes acting at a broader geographic scale, within river drainage which comprise divergent guppy lineages; suggesting that evolutionary history and processes such as genetic drift and gene flow also contribute substantially to these relationships. Our results highlight that MHC diversity is correlated to the level of diversity of parasite communities, yet, by considering a single parasite type, we only found limited support for the Hamilton–Zuk hypothesis. Rather, the long-term evolutionary history and contemporary demographic processes are more important factors shaping MHC diversity across populations. Our work demonstrates the importance of examining whole parasite communities within broader evolutionary contexts.

This readme file was generated on 2025-09-27 by Allegra Love

-
General information
-
1. Title of dataset:

2. Dataset DOI: NA

3. Long-term contact
 Name: Kiyoko Gotanda
 ORCID: 0000-0002-3666-0700
 Institution: Brock University
 Email: kgotanda@brocku.ca

4. Author
 Name: Allegra Love
 ORCID: 0000-0002-4637-6850
 Institution: University of Guelph
Redpath Museum, McGill Unviersity
Department of Biology, McGill University
 
Name: Jackie Lighten
 ORCID: 0000-0002-4228-1037
 Institution: Marine Gene Probe Laboratory, Department of Biology, Dalhousie University

 Name: Cock van Oosterhout
 ORCID: 0000-0002-5653-738X
 Institution: School of Environmental Sciences, University of East Anglia

 Name: Alexander S.T. Papdopulos
 ORCID: 0000-0001-6589-754X
 Institution: Marine Gene Probe Laboratory, Department of Biology, Dalhousie University

 Name: Stanley D. King
 ORCID: NA
 Institution: Marine Gene Probe Laboratory, Department of Biology, Dalhousie University

 Name: Ian G. Paterson
 ORCID: NA
 Institution:

 Name: Lari C. Delaire
 ORCID: NA
 Institution: Redpath Museum, McGill Unviersity
Department of Biology, McGill University

 Name: Lyndsey Baillie
 ORCID: NA
 Institution: Marine Gene Probe Laboratory, Department of Biology, Dalhousie University

 Name: Ian R. Bradbury
 ORCID: 0000-0002-8152-4943
 Institution: Department of Fisheries and Oceans

 Name: Janay A. Fox
 ORCID: 0000-0002-7895-2357
 Institution: Redpath Museum, McGill Unviersity
Department of Biology, McGill University

 Name: Felipe Perez-Jvostov
 ORCID: 0000-0003-0822-5039
 Institution: Department of Biology, McGill University

 Name: Felipe Dargent
 ORCID: 0000-0002-4510-0086
 Institution: Department of Biology, McGill University

 Name: Marilyn Scott
 ORCID: 0000-0002-3553-4550
 Institution: Institute of Parasitology, Macdonald Campus of McGill University

 Name: Gregor F. Fussmann
 ORCID: 0000-0001-9576-0122
 Institution: Department of Biology, McGill University

 Name: Andrew P. Hendry
 ORCID: 0000-0002-4807-6667
 Institution: Redpath Museum, McGill Unviersity
Department of Biology, McGill University

 Name: Paul Bentzen
 ORCID: 0000-0003-4288-7730
 Institution: Marine Gene Probe Laboratory, Department of Biology, Dalhousie University

 Name: Kiyoko M. Gotanda
 ORCID: 0000-0002-3666-0700
 Institution: Redpath Museum, McGill Unviersity
Department of Biology, McGill University
Department of Biological Sciences, Brock University

5. Description of the dataset: Data used in analysis from "Interpreting relationships among MHC, parasites, and secondary sexual colouration in a natural system".

6. Date of data collection: 2009-2010

7. Geographic location of the data collection: Trinidad and Tobago, see figure 1.

8. Funding information: Funding for this research was provided by the Natural Sciences and Engineering Research Council of Canada (NSERC). AL was supported by a Natural Sciences and Engineering Research Council (NSERC) Postgraduate scholarship—Doctoral (#PGSD - 588909 - 2024). KMG was supported by an NSERC Vanier, Banting, and Discovery Grant.
 
-
Sharing/access information
-
1. Licenses/restrictions placed on the dataset: CC-BY 4.0

2. Links to publications that cite or use the dataset: TBD

3. Links/relationships to related datasets: MHC sequencing data used to generate richness metrics for the associated publication has been submitted to the GenBank database (KR870052-KR870125) and the NCBI database (KF321642.1–KF321728.1 (PopSet: 544451456), and KT003989.1–KT004363.1 (PopSet: 1033321404). 

4. Data sources: NA

5. Dataset citation: TBD

-
Folder and file overview
-
1. File List: 

[code]: [contains all scripts to run analysis and generate figures]

[code/01-data-prep.rmd]: [Uses raw data files to generate data files that are used in analysis]

[code/02-data-analysis.rmd]: [Uses data outputs from code/01-data-prep.rmd to run analyses as outlined in the manuscript. Saves results from these analyses in output/ for use in figure generation]

[code/03-figures.rmd]: [generates figures in manuscript, saves to Figures/]

[Figures]: [for figures generated in code/03-figures.rmd]

[output]: [for files generated from data prep and analysis.]

[data]: [place files from data repository here, required to run scripts]

2. Relationship between files, if important:

Must run files in code/ in numerical order (e.g., 01-data-prep.rmd needs to be run to run 02-data-analysis.rmd)
