# Dublin Tram GAEN Dataset
Measurements of Google/Apple Exposure Notification Attenuation Durations Taken on a Dublin Tram and reported in:

"Measurement-Based Evaluation Of Google/Apple Exposure Notification API For Proximity Detection In A Light-Rail Tram", Douglas J. Leith, Stephen Farrell, SCSS Tech Report 23rd June 2020.

There dataset contains the following files:

1. dublintram_dataset_attenuations.txt. Each row corresponds to a pair of handsets at one distance. Each column to the attenuation duration (in minutes) at a given range of attenuation levels, E.g. column one is for attenuation range 48-50dB, column two for 50-52dB and so on.
2. dublintram_dataset_distances.txt. Each row contains the estimated distance (in metres) between a pair of handsets, with each row corresponding to the same row in file dublintram_dataset_attenuations.txt.
3. dublintram_dataset_distances.txt.  Each row gives the indices of the pair of handsets corresponding to the measurements in dublintram_dataset_attenuations.txt 
4. cwa_config.txt, immuni_config.txt.  Configuration settings for the Corona Warn and Immuni contact tracing apps,m downloaded 22nd June 2020
5. EN Calibration June 13th.csv.  Google GAEN calibration values for a range of phone models.
