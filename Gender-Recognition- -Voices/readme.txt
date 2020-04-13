Recognition-Voices-withMachineLearning
Machine Learning/ Classification Project/Python
Goals
To predict gender with corresponding voice and speech features

Data Sets of 3,168 observations with 21 variables listed below.
1 target variable:
tag (male or female)
20 arguments:

meanfreq: average frequency (in kHz)
sd: standard frequency deviation
median: median frequency (in kHz)
Q25: first quantity (in kHz)
Q75: third quantity (in kHz)
IQR: quarter interval (in kHz)
distortion: distortion (see note in spectrum description)
wolf: kurtosis (see note in spectrum definition)
sp.ent: spectral entropy
SFM: spectral flatness
mod: mod frequency
centroid: frequency centroid (see spectrum)
meanfun: average base frequency measured over the acoustic signal
minfun: minimum base frequency measured over an acoustic signal
maxfun: maximum base frequency measured over the acoustic signal
meandom: dominant frequency average measured along the acoustic signal
mindom: minimum dominant frequency measured across the acoustic signal
maxdom: maximum dominant frequency measured over acoustic signal
dfrange: dominant frequency range measured across the acoustic signal
modindx: modulation index

Run the algorithms and estimate whether the sound samples are Male or Female in the form of 0's and 1's.



