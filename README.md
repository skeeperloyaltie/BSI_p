## Description
- The purpose of this script is to analyze EEG data collected from a single subject during a cognitive task experiment. The script uses the MNE-Python library to perform EEG data analysis and visualization.

- The script starts by loading the EEG data from a .edf file using MNE-Python's mne.io.read_raw_edf() function. It then visualizes the raw EEG data and the stimulus channel using Plotly, a Python graphing library.

- The script then filters the raw data and applies Independent Component Analysis (ICA) to remove any artifacts from the EEG data. The ICA-corrected data is then visualized using Plotly.

- Next, the script extracts the events from the stimulus channel and creates an event dictionary for the different types of stimuli. The events are used to create epochs for each type of stimulus, which are then used to compute the average brain activity for each stimulus type.

- The script also uses MNE-Python's topomap visualization function to display the localized brain activity for each stimulus type.

- Finally, the script analyzes the EEG data during the button press event and visualizes the average brain activity for this event.

Overall, this script provides a comprehensive analysis of EEG data and can be used as a starting point for further analysis or as a reference for others interested in analyzing EEG data using MNE-Python.
