[Data used available on this Kaggle Respiratory Sound Database.](https://www.kaggle.com/datasets/vbookshelf/respiratory-sound-database/data)

<h2>
  〰️ CNN for automated diagnosis of respiratory diseases in audio files
</h2>

Respiratory sounds play a crucial role in assessing respiratory well-being and identifying respiratory ailments. The sound emitted when a person breathes is directly related to air movement, changes within lung tissue and the position of secretions within the lung. For instance, the presence of wheezing is a common indication of obstructive airway conditions such as asthma or chronic obstructive pulmonary disease (COPD).

Modern technology, such as digital stethoscopes and various recording methods, enables the capture of these sound patterns. The digital data thus acquired opens up exciting possibilities for the utilization of machine learning in the automated diagnosis of respiratory disorders.

<br />

<div align="center">
  
https://github.com/Smainfet/Smainfet/assets/97527246/429bee34-eb3f-4bcb-b306-8821a1b1ba70

<sub><sup> *Audio file of a patient with bronchiectasis* </sup></sub>
</div>

<br />

I have worked on implementing a Convolutional Neural Network (CNN) used to identify respiratory diseases in audio files. The CNN is fed with Mel-Spectrograms, Chromagrams, and Mel-frequency cepstrum features extracted from the input audio files. 

<div align="center">
<img width="300" alt="image" src="https://github.com/Smainfet/Smainfet/assets/97527246/7e07e2d2-e2e4-41d9-b562-648fed4a10c0">
</div>

<br />

During processing, audio clips are split into 6-second segments, with zero-padding added if necessary. During training, Mel-Spectrograms, Chromagrams, and Mel-frequency cepstrum features are extracted from the audio files to assist the network in identifying features associated with respiratory diseases occurring at arbitrary times within the recordings.

<div align="center">
<img width="1081" alt="image" src="https://github.com/Smainfet/Smainfet/assets/97527246/ce182e8d-5e19-4ec9-8a85-6aa7a5d72cc8">
</div>
