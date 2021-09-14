## Part of Project: Classifying Audio as Extremist Propaganda or Not


### Method: Use STFTs to detect the presence of extremist music in propaganda audio


*Files in Repo:

- STFT_Music_Recognition_Final.ipynb --> Python notebook where the entire core code lies
- Music_Recognition_Results_Visualisation.ipynb --> Python notebook just for results' visualisations (manually done)

- Extreme_Hash_Table.pkl --> Hash table object with fingerprints of all extremist songs
- Pop_Extreme_Hash_Table.pkl --> Hash table object with fingerprints of some extremist songs and some pop songs
- Pop_Hash_Table.pkl --> Hash table object with fingerprints of 11 pop songs

- Extreme_database_songs_df --> Dataframe object storing a list of extremist songs the system trained on
- Pop_extreme_database_songs_df --> Dataframe object storing a list of extremist/pop songs the system trained on
- Pop_database_songs_df --> Dataframe object storing a list of pop songs the system trained on

- whole_clips_results_df --> Dataframe of whole clip test results
- *.csv files --> result file for each of the three tests performed
