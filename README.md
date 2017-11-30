# FANTASIA
## About

This repository contains the data used in the article _Automatic composition of descriptive music: A case study of the relationship between image and sound_ published in the 6th International Workshop on Computational Creativity, Concept Invention, and General Intelligence (C3GI). Data structure is explained in detail in the article. <br /><br />
**Abstract**<br />
Human beings establish relationships with the environment mainly through sight and hearing. This work focuses on the concept of descriptive music, which makes use of sound resources to narrate a story. The Fantasia film, produced by Walt Disney was used in the case study. One of its musical pieces is analyzed in order to obtain the relationship between image and music. This connection is subsequently used to create a descriptive musical composition from a new video. Naive Bayes, Support Vector Machine and Random Forest are the three classifiers studied for the model induction process. After an analysis of their performance, it was concluded that Random Forest provided the best solution; the produced musical composition had a considerably high descriptive quality.
<br />

## Data
1. **Nutcracker_data.arff**: Image descriptors and the most important sound of each frame from the fragment "The Nutcracker Suite" in film Fantasia. Data stored into ARFF format.
2. **Firebird_data.arff**: Image descriptors of each frame from the fragment "The Firebird" in film Fantasia 2000. Data stored into ARFF format.
3. **Firebird_midi_prediction.csv**: Frame number of the fragment "The Firebird" in film Fantasia 2000 and the sound predicted by the system encoded in MIDI. Data stored into CSV format.
4. **Firebird_prediction.mp3**: Audio file with the synthesizing of the prediction data for the fragment "The Firebird" of film Fantasia 2000.

## License
Data is available under MIT License. To make use of the data the article must be cited.
