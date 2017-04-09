# ath9k_csi_experiment_data
Data files captured using ath9k cards

Recordings for distances between 0 and 30m.
Filenames:
<Distance>_<Channel Section>_<recording No.>.dat

**Channel Sections**
0. 1-14
1. 36-64
2. 100-140
3. 149-165

The recordings were done with HT40+. Each channel was recorded for two seconds, then the channel was switched to the next higher one (using hostapd channel switch announcement). The client was sending packages every 500µs. 

