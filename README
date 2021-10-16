Dataset description
This dataset is part of a bigger dataset of intracranial EEG (iEEG)  called RESPect (Registry for Epilepsy Surgery Patients), a dataset recorded at the University Medical Center of Utrecht, the Netherlands.
It consists of 12 patients: six patients recorded intraoperatively using electrocorticography (acute ECoG), six patients with long-term recordings (3 patients recorded with ECoG and 3 patients recorded with stereo-encephalography SEEG). For a detailed description see (Demuru M, van Blooijs D, Zweiphenning W, Hermes D, Leijten F, Zijlmans M, on behalf of the RESPect group. “A Practical Workflow for Organizing Clinical Intraoperative and Long-Term iEEG data in BIDS”.).


This data is organized according to the Brain Imaging Data Structure specification. A community- driven specification for organizing neurophysiology data along with its metadata. For more information on this data specification, see https://bids-specification.readthedocs.io/en/stable/


Each patient has their own folder (e.g., `sub-RESP0280`) which contains the iEEG recordings data for that patient, as well as the metadata needed to understand the raw data and event timing.


Two different implementation of the BIDS structure were done according to the different type of recordings (i.e. intraoperative or long-term)
Intraoperative ECoG
Surgery with intraoperative ECoG is composed of three main situations that can be logically grouped into BIDS sessions:


* Pre-resection sessions, consisting of all recordings (with different configurations of the grid and strips/depth) carried out before the surgeon has started the planned resection.


* Intermediate sessions, consisting of all subsequent recordings performed before any iterative extension of the resection area.


* Post-resection sessions, consisting of all the recordings performed after the last resection.


Each situation is labelled with an increasing number starting from 1, indicative of the period in time respective to the surgical resection and a consecutive letter (starting from A) indicative of the position of the grid and strip/depth for a given session.
As an example see patient RESP0280 who had 4 sessions recorded: two pre-resection sessions, one intermediate sessions and one post-resection session. The first session is SITUATION1A consisting of the first recording, then the grid was moved to another position, resulting in SITUATION1B. After that, the surgeon resected part of the brain and then there was another recording(SITUATION2A). Finally the surgeon applied a resection for the last time and the recording after that was defined as SITUATION3A.


Long-term iEEG
In long-term recordings, data that are recorded within one monitoring period are logically grouped in the same BIDS session and stored across runs indicating the day and time point of recording in the monitoring period.
If extra electrodes were added/removed during this period, the session was divided into different sessions (e.g. ses-1A and ses-1b).
We use the optional run key-value pair to specify the day and the start time of the recording (e.g. run-021315, day 2 after implantation, which is day 1 of the monitoring period, at 13:15).
The task key-value pair in long-term iEEG recordings describes the patient’s state during the recording of this file. Different tasks have been defined, such as “rest” when a patient is awake but not doing a specific task, “sleep” when a patient is sleeping the majority of the file, or “SPESclin” when the clinical SPES protocol has been performed in this file. Other task definitions can be found in the annotation syntax (https://github.com/UMCU-EpiLAB/umcuEpi_longterm_ieeg_respect_bids/master/manuals/IFU_annotatingtrc_ECoG).


License
This dataset is made available under the Public Domain Dedication and License CC v1.0, whose full text can be found at
https://creativecommons.org/publicdomain/zero/1.0/.
We hope that all users will follow the ODC Attribution/Share-Alike Community Norms (http://www.opendatacommons.org/norms/odc-by-sa/);
in particular, while not legally required, we hope that all users of the data will acknowledge by citing
Demuru M, van Blooijs D, Zweiphenning W, Hermes D, Leijten F, Zijlmans M, on behalf of the RESPect group. “A Practical Workflow for Organizing Clinical Intraoperative and Long-Term iEEG data in BIDS”. Submitted to Neuroinformatics.
in any publications.

Code available at: https://github.com/UMCU-EpiLAB.

Acknowledgements
We would like to thank the patients for providing their data for this dataset, the RESPect team of University Medical Center of Utrecht, for the acquisition of the dataset.
Please cite Demuru M, van Blooijs D, Zweiphenning W, Hermes D, Leijten F, Zijlmans M, on behalf of the RESPect group. “A Practical Workflow for Organizing Clinical Intraoperative and Long-Term iEEG data in BIDS”. Submitted to Neuroinformatics.
in any publications.
