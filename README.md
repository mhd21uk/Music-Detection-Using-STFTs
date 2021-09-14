## Part of Project: Classifying Audio as Extremist Propaganda or Not


### Method: Use STFTs to detect the presence of extremist music in propaganda audio

<hr style="height:1px;border:none;color:#333;background-color:#333;" />

<b>Note: The following libraries are no longer available. Alternatives need to be provided in order to output a confusion matrix, and more importantly, to produce the spectrograms</b>

-from pandas_ml import ConfusionMatrix <br>
-import librosa <br>
-import librosa.display <br>

<b> In the meantime, previously computed hash tables have already been created and can be loaded in (code to load the hash tables in already present in the notebook) </b>

<hr style="height:1px;border:none;color:#333;background-color:#333;" />

### Beneficiaries:

The main beneficiaries of this project are the major social media platforms, such as Facebook and YouTube.
These platforms would be able to use, and build on, the created models to automatically detect and filter
out extremist propaganda, which significantly aids their content moderating teams. This project also serves
a global benefit by reducing terrorist media exposure, making recruitment much more difficult, and hence
works to erase toxic extremist ideology.

<hr style="height:1px;border:none;color:#333;background-color:#333;" />

### The Method in Detail:

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
