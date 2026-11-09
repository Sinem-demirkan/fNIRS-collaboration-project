Both the fNIRS collaboration study Manual and the Rapport Annotation Pipeline were authored by Sinem Demirkan during her position as a Research Engineer working with Professor Justine Cassell at Articulabo, from January 2024 to August 2025.

These documents provide guidelines for experimental setup, data collection, rapport annotation, and post-collection processing, contributing to the documentation and reproducibility of the research workflows. These documents were used in training all new people joining to the 3-Task/4-tasks team from **September 2024** and on.

This repository documents the practical setup and operation of a two-participant fNIRS hyperscanning experiment. It is intended to help experimenters prepare the equipment (setup fNIRS software and start the Psychopy script), coordinate participant sessions, collect synchronized recordings, and complete post-session checks consistently. Two datasets were collected as part of the experimental study:

**1. Adult Pilot Dataset (September–December 2024)**

A pilot dataset comprising **20 dyads** was collected at the **Inria Paris Research Centre, France**, by Sinem Demirkan, Cindy de Arajullo Silva, Hasan Onur Keles, Sophie Etling, Barokshana Baskaran, and Gabrielle Alimi (September–December 2024), and Reem al Najjar (November–December 2024).

**2. School Dataset (April–July 2025)**

A second dataset comprising **13 dyads** was collected between April and July 2025 at **École élémentaire Boileau (17 rue Boileau, 75016 Paris, France)**, involving pairs of school-aged children. This data collected by main experimenters (Sinem Demirkan, Cindy de Arajullo Silva, Hasan Onur Keles, Reem al Najjar), and invaluable work by Barokshana Baskaran, Gabrielle Alimi and Imani Stone.

**fNIRS Data Processing and Analysis**
My data analysis contributions included aligning paired recordings, preparing data for analysis in 30-second segments, and developing an exploratory computational workflow for analyzing inter-brain synchrony (IBS) in fNIRS hyperscanning data.

The analysis notebook includes:

- Loading and preprocessing paired fNIRS recordings.

- Checking temporal alignment using experimental event annotations.

- Identifying experimental conditions, including solo, collaboration, and free discussion.

- Computing wavelet-transform coherence (WTC) between participants' neural signals.

- Analyzing coherence in 30-second intervals.

- Extracting and aggregating coherence measures across selected brain regions, including the superior temporal sulcus (STS) and temporoparietal junction (TPJ).

I worked closely with Patrice Fortin, from Guillaume Dumas's team, on the IBS analysis workflow. This work provided a substantial starting point for subsequent IBS analyses, and I shared the pipeline with new team members upon request to support continuity and facilitate further development.

ACKNOWLEDGMENTS AND CREDITS

Professor Justine Cassell made this research possible and I thank her for the opportunity to work with her research team at Articulabo. I learnt a lot during my 1 year and 8 months of being a research engineer with her.

I would like to thank Cindy de Arajullo Silva and Hasan Onur Keles for their invaluable contributions to operationalizing the experimental workflow. Particularly their addition to the team made it possible to fix the network configurations, pilot studies, and input into the experimental procedures such as aligning data streams between July 2024-September 2024 prior to first real data collection. Their work was especially valuable during the preparation and we worked colaboratively as a team in implementing the adult pilot study.

For the Rapport Annotation Pipeline, I thank Clara Coridon for the helpful discussions, who worked as an intern alongside me on rapport analysis and contributed to the work described in the Post-collection Annotation Processing section.
