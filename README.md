fNIRS collaboration study Manual and the Rapport Annotation Pipeline are entirely written by me Sinem Demirkan during her position as a Research Engineer working with Professor Justine Cassell at Articulabo, from **January 2024 to August 2025**.

### 1. Development and Documentation of the 3-Task/4-Task Experimental Pipeline

I developed and documented the **3-Task/4-Task experimental pipeline**, along with a detailed experimental manual, to support the standardized setup, execution, and data collection of two-participant fNIRS hyperscanning experiments.

My contributions include:

- **Experimental setup:** Established procedures for configuring fNIRS hardware and software, network connections, PsychoPy scripts, and recording equipment.
- **Experiment implementation:** Documented procedures for coordinating participant sessions and collecting synchronized fNIRS, video, and audio recordings.
- **Data management:** Established guidelines for organizing recordings and performing post-session checks.
- **Documentation and training:** Authored a step-by-step experimental manual used to train new members joining the 3-Task/4-Task research team from **September 2024 onward**.

The pipeline supported the collection of **two datasets (adult and school-aged participants)**, described further in Section 5, and contributed to the consistency, reproducibility, and continuity of the experimental workflow.

### 2. Development of the PsychoPy Experimental Script and LSL Integration (March 2024)

To operationalize the experimental framework conceptualized by **Professor Justine Cassell** and presented in the study protocol paper [*Bringing together multimodal and multilevel approaches to study the emergence of social bonds between children and improve social AI*](https://doi.org/10.3389/fnrgo.2024.1290256) (Bonnaire, Dumas, & Cassell, 2024), I proposed using **PsychoPy**, drawing on my experience with the platform during previous research internships.

In **March 2024**, during my third month as a Research Engineer, I developed the initial PsychoPy script, which included:

- **Experimental workflow:** Designed sequential routines for participant instructions, baseline recordings, solo brainstorming, and collaboration, with subsequent versions supporting additional experimental phases.
- **LSL integration:** Implemented a Lab Streaming Layer (LSL) connection to transmit event markers to the fNIRS recording software, enabling synchronization of experimental events with neural recordings.
- **Task presentation:** Developed a structured interface for presenting instructions, visual stimuli, and transitions between experimental phases.
This script I created served as the foundation for subsequent **3-Task/4-Task experiments**. Later we (me and Cindy) made few modifications to the script (changing task durations, stimuli, and experimental conditions as needed) but not the triggers or how the connection is established between devices.

This implementation established the experimental software and synchronization workflow used and adapted throughout the project.

### 3. Development and Documentation of the Interpersonal Rapport Annotation Pipeline

I designed and developed an **interpersonal rapport annotation pipeline** and authored its accompanying experimental manual to support the systematic collection and analysis of rapport ratings from video-recorded dyadic interactions.

The pipeline enables researchers to **create new experiments or reuse my existing experimental design** using crowdsourcing platforms such as Amazon Mechanical Turk (AMT) and Prolific.

My contributions include:

- **Experimental design:** Developed reusable annotation tasks for evaluating interpersonal rapport in 30-second video segments.
- **Experiment implementation:** Established procedures for experiment setup, participant recruitment, and data collection.
- **Data processing and analysis:** Documented methods for extracting and aggregating annotations, assessing inter-rater reliability, and calculating consolidated rapport scores.
- **Documentation:** Authored a step-by-step manual to facilitate reproducibility and reuse by other researchers.

**Acknowledgment:** Clara Cordion contributed to the post-collection annotation processing and rapport analysis work.

### 4. fNIRS Data Processing and Analysis ###
My data analysis contributions included aligning paired recordings, preparing data for analysis in 30-second segments, and developing an exploratory computational workflow for analyzing inter-brain synchrony (IBS) in fNIRS hyperscanning data.

The analysis notebook includes:

- Loading and preprocessing paired fNIRS recordings.

- Checking temporal alignment using experimental event annotations.

- Identifying experimental conditions, including solo, collaboration, and free discussion.

- Computing wavelet-transform coherence (WTC) between participants' neural signals.

- Analyzing coherence in 30-second intervals.

- Extracting and aggregating coherence measures across selected brain regions, including the superior temporal sulcus (STS) and temporoparietal junction (TPJ).

I worked closely with Patrice Fortin, from Guillaume Dumas's team, on the IBS analysis workflow. This work provided a substantial starting point for subsequent IBS analyses, and I shared the pipeline with new team members upon request to support continuity and facilitate further development.

### 5. Data Collection

#### 5.1 Adult Pilot Dataset (September–December 2024)

A pilot dataset comprising **20 dyads** was collected at the **Inria Paris Research Centre, France**.

I was responsible for **coordinating the dataset acquisition, organizing experimental sessions, and training all team members involved in data collection**.

Data collection was conducted by **Sinem Demirkan, Cindy de Arajullo Silva, Hasan Onur Keles, Sophie Etling, Barokshana Baskaran, and Gabrielle Alimi (September–December 2024)**, and **Reem al Najjar (November–December 2024)**.

#### 5.2 School Dataset (April–July 2025)

A second dataset comprising **13 dyads** was collected between April and July 2025 at **École élémentaire Boileau (17 rue Boileau, 75016 Paris, France)**, involving pairs of school-aged children.

Data collection was primarily conducted by **Sinem Demirkan, Cindy de Arajullo Silva, Hasan Onur Keles, and Reem al Najjar**, with invaluable contributions from **Barokshana Baskaran, Gabrielle Alimi, and Imani Stone**.

My contributions included:

- **Data collection:** Conducted experimental sessions and coordinated the acquisition of multimodal recordings.
- **Data management and storage:** Organized the collected data on Box, including systematic file renaming, folder structuring, and maintaining consistent data organization across participants and sessions.
- **Experimental documentation:** Maintained an experimental logbook recording session details, technical difficulties, unexpected events, and issues encountered during data collection. I subsequently digitized and organized these records into a structured document to facilitate troubleshooting, data quality assessment, and subsequent analyses.

#### 5.3 Additional Children's Dataset (July–August 2025)

A third dataset comprising **8 dyads** was collected during July–August 2025 at Inria Paris Center, involving pairs of younger children.

Data collection was conducted by Sinem Demirkan, Cindy de Arajullo Silva, Reem al Najjar, and Barokshana Baskaran.

#### 5.4 fNIRS Equipment Configuration, Preparation, and Technical Coordination

In addition to data collection, I was responsible for preparing, configuring, and maintaining the fNIRS equipment, coordinating technical support and procurement, and training new team members.

My contributions included:

- **fNIRS cap configuration:** Created the optode montage using NIRSite, based on the experimental framework described in Bonnaire, Dumas, and Cassell (2024).
- **Cap preparation and training:** Assembled the fNIRS caps, trained incoming interns in cap preparation and optode placement, and worked alongside them on cap assembly.
- **Equipment procurement and coordination:** Served as the primary point of contact with **NIRx**, particularly Felix Topfner (for most of 2024), followed by Giovanni Hering, Maria Adelia de Aratanha, and Elina Zmeykina, coordinating cap orders, additional equipment purchases, technical inquiries, and follow-ups.
- **Software maintenance:** Managed compatible versions of Aurora and Hyperscan to maintain a consistent and functional fNIRS acquisition setup.
- **Conducting interviews with the new interns**

These contributions supported the continuity of experimental operations, standardized equipment preparation, and reliable multimodal data collection across the different studies.

**GENERAL ACKNOWLEDGMENTS AND CREDITS (because, it is important)**

Professor Justine Cassell made this research possible and I thank her for the opportunity to work with her research team at Articulabo. I learnt a lot during my 1 year and 8 months of being a research engineer and happy to have contributed significantly to this project.

I worked closely with Cindy de Arajullo Silva and Hasan Onur Keles in operationalizing the experimental workflow. Particularly their addition to the team made it possible to fix the network configurations, pilot studies, and input into the experimental procedures such as aligning data streams between July 2024-September 2024 prior to first real data collection. Their work was especially valuable during the preparation and we worked colaboratively as a team in implementing the adult pilot study.

For the Rapport Annotation Pipeline, I thank Clara Coridon for the helpful discussions, who worked as an intern alongside me on rapport analysis and contributed to the work described in the Post-collection Annotation Processing section.

Merci aussi à Julie Bonnaire qui m'a beaucoup aidé à mon intégration à l'équipe!
