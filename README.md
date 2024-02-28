# LearningToChoose  

### Data shared here are from:
Learning to Choose: Behavioral Dynamics Underlying the Initial Acquisition of Decision Making  
Samantha R. White, Michael W. Preston, Kyra Swanson, Mark Laubach  
Department of Neuroscience, American University, Washington, DC, USA  

### Behavior_White_2024.csv

This file contains trial-by-trial data for all rats in the study. Columns are:  

name		name of the rat  
date		date of the experiment  
session		prechoice (prior to choice learning), choice (session with single and dual offer stimuli), between (session with only single offer trials)  
time		experimental time of the trial  
trialtype	0 = single offer, 1 = dual offer  
cue		2 = 2 LEDs, 8 = 8 LEDs  
sucrose	4 = 4% sucrose, 16 = 16% sucrose  
side		0 = response to left port, 1 = response to right port  
error		0 = response to illuminated port, 1 = response to non-illuminated port  
choice		response latency in seconds  
reward		time to collect reward in seconds  
iti		inter-trial interval in seconds  


### Latencies_HighValPrefs_White_2024.csv

This file contains measures of median response latency and high-value preference. Columns are:  

Session	session number  
Rat		ID for Rat  
trialtype	0 = single offer, 1 = dual offer  
cue		2 = 2 LEDs, 8 = 8 LEDs  
medRT		median response latency in seconds  
HVpref		preference for high-value stimulus on dual-offer trials  


### median_latencies_White_2024.csv

This file contains measures of median response latency for the four types of trials. Columns are:  

Session	session number  
Rat		ID for Rat  
HiSO		median response latency for high-value, single-offer trials  
LoSO		median response latency for low-value, single-offer trials  
HiDO		median response latency for high-value, dual-offer trials  
LoDO		median response latency for low-value, dual-offer trials  


### ExGauss_White_2024.csv

This file contains parameters from the ExGauss models for each rat and session. Columns are:  

Session	session number  
Rat		ID for Rat  
trialtype	0 = single offer, 1 = dual offer  
cue		2 = 2 LEDs, 8 = 8 LEDs  
mu		Gaussian component of latency distribution  
tau		Exponential component of latency distribution  


### pyDDM_Results_White_2024.csv

This file contains parameters from the pyDDM models for each rat and session. Columns are:  

Session			session number  
Rat				ID for Rat  
Drift Rate, Threshold, NDT	Parameters from the DDM models  
