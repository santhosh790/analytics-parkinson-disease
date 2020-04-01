# Parkinson Disease Analytics
This repository is for the analysis of Parkinson disease dataset available publicly

## Introduction
Parkinson disease affects the nervous system of human being and creates a movement disorder. It gradually start in the system and gets worser over time. People with this disease find it very difficult to balance themselves while walking or talking. This occurs due to the drop in dopamine level in human brain. Early symptoms for this disease are tremor in hands or fingers, slowed movement and the changes in voice and writing.

Diagnosing this disease earlier stages is imperative to control or cure. Occurrence of one or more symptoms can be confirmed to be affected by parkinson. But, there are other similar diseases also. So, proper physician diagnosis is important.

## Source data collection details

###### Collection Source: Physician's Examination using phonation.
###### Data Extraction: Phonation of vowel /a/ using the microphone at 44.1 KHz
##### Attribute Extraction methods: Various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment. (from dataset source)

## Details of the extracted dataset
- ###### Number of Instances (rows): 756
- ###### Number of Attributes (columns or features): 754
- ###### Number of unique people tested: 252 [3 voice records per individual]
- ###### Number of parkinson patients: 188 [107 Men, 81 Women]
- ###### Number of normal people: 64 [41 Men, 23 Women]

Age is not mentioned in the dataset. But, the dataset source mentioned PD patients ages ranging from 33 to 87 and normal people ages ranging from 41 to 82. 

##### Target variable
- class: 0 (Disease negative), 1 (Disease positive)

## Data Exploration and Analytics

1. Exploring data
2. Person based exploration
3. Correlation of independent variables on target variable
4. Linear Regression model
5. ROC-AUC Curve

#### Nature of Task: **Classification** 

#### RESULT: Minimum number of features required to explain Parkinson Disease with 70% ROC - AUC : 2 (DFA and RPDE)