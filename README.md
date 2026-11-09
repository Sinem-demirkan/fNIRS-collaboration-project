Both the fNIRS collaboration study Manual and the Rapport Annotation Pipeline were authored by Sinem Demirkan during her position as a Research Engineer working with Professor Justine Cassell at Articulabo, from **January 2024 to August 2025**.

### 1. Development and Documentation of the 3-Task/4-Task Experimental Pipeline

I developed and documented the **3-Task/4-Task experimental pipeline**, along with a detailed experimental manual, to support the standardized setup, execution, and data collection of two-participant fNIRS hyperscanning experiments.

My contributions include:

- **Experimental setup:** Established procedures for configuring fNIRS hardware and software, network connections, PsychoPy scripts, and recording equipment.
- **Experiment implementation:** Documented procedures for coordinating participant sessions and collecting synchronized fNIRS, video, and audio recordings.
- **Data management:** Established guidelines for organizing recordings and performing post-session checks.
- **Documentation and training:** Authored a step-by-step experimental manual used to train new members joining the 3-Task/4-Task research team from **September 2024 onward**.

The pipeline supported the collection of **two datasets (adult and school-aged participants)**, described further in Section 4, and contributed to the consistency, reproducibility, and continuity of the experimental workflow.

### 2. fNIRS DATA PROCESSING ANALYSIS ###
My data analysis contributions included aligning paired recordings, preparing data for analysis in 30-second segments, and developing an exploratory computational workflow for analyzing inter-brain synchrony (IBS) in fNIRS hyperscanning data.

The analysis notebook includes:

- Loading and preprocessing paired fNIRS recordings.

- Checking temporal alignment using experimental event annotations.

- Identifying experimental conditions, including solo, collaboration, and free discussion.

- Computing wavelet-transform coherence (WTC) between participants' neural signals.

- Analyzing coherence in 30-second intervals.

- Extracting and aggregating coherence measures across selected brain regions, including the superior temporal sulcus (STS) and temporoparietal junction (TPJ).

I worked closely with Patrice Fortin, from Guillaume Dumas's team, on the IBS analysis workflow. This work provided a substantial starting point for subsequent IBS analyses, and I shared the pipeline with new team members upon request to support continuity and facilitate further development.

### 3. Development and Documentation of the Interpersonal Rapport Annotation Pipeline

I designed and developed an **interpersonal rapport annotation pipeline** and authored its accompanying experimental manual to support the systematic collection and analysis of rapport ratings from video-recorded dyadic interactions.

The pipeline enables researchers to **create new experiments or reuse my existing experimental design** using crowdsourcing platforms such as Amazon Mechanical Turk (AMT) and Prolific.

My contributions include:

- **Experimental design:** Developed reusable annotation tasks for evaluating interpersonal rapport in 30-second video segments.
- **Experiment implementation:** Established procedures for experiment setup, participant recruitment, and data collection.
- **Data processing and analysis:** Documented methods for extracting and aggregating annotations, assessing inter-rater reliability, and calculating consolidated rapport scores.
- **Documentation:** Authored a step-by-step manual to facilitate reproducibility and reuse by other researchers.

**Acknowledgment:** Clara Cordion contributed to the post-collection annotation processing and rapport analysis work.

###4. DATA COLLECTION###

**4.1 Adult Pilot Dataset (September–December 2024)**

A pilot dataset comprising **20 dyads** was collected at the **Inria Paris Research Centre, France**, by Sinem Demirkan, Cindy de Arajullo Silva, Hasan Onur Keles, Sophie Etling, Barokshana Baskaran, and Gabrielle Alimi (September–December 2024), and Reem al Najjar (November–December 2024).

**4.2 School Dataset (April–July 2025)**

A second dataset comprising **13 dyads** was collected between April and July 2025 at **École élémentaire Boileau (17 rue Boileau, 75016 Paris, France)**, involving pairs of school-aged children. This data collected by main experimenters (Sinem Demirkan, Cindy de Arajullo Silva, Hasan Onur Keles, Reem al Najjar), and invaluable work by Barokshana Baskaran, Gabrielle Alimi and Imani Stone.

**GENERAL ACKNOWLEDGMENTS AND CREDITS (because, it is important)**

Professor Justine Cassell made this research possible and I thank her for the opportunity to work with her research team at Articulabo. I learnt a lot during my 1 year and 8 months of being a research engineer with her.

I would like to thank Cindy de Arajullo Silva and Hasan Onur Keles for their invaluable contributions to operationalizing the experimental workflow. Particularly their addition to the team made it possible to fix the network configurations, pilot studies, and input into the experimental procedures such as aligning data streams between July 2024-September 2024 prior to first real data collection. Their work was especially valuable during the preparation and we worked colaboratively as a team in implementing the adult pilot study.

For the Rapport Annotation Pipeline, I thank Clara Coridon for the helpful discussions, who worked as an intern alongside me on rapport analysis and contributed to the work described in the Post-collection Annotation Processing section.
