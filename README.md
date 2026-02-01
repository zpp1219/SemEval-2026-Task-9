# SemEval-2026-Task-9
Code for SemEval 2026 Task 9: Detecting Multilingual, Multicultural And Multievent Online Polarization
# Subtask 1: Polarization Detection (True/False)
Binary classification to determine whether a post contains polarized content (polarized or not polarized).

Development
###Bag_of_Words_model
Your Results
Language	Accuracy	Precision	Recall	F1 Binary	F1 Macro	F1 Micro
EN
English
0.7218	0.675	0.5294	0.5934	0.691	0.7218
SP
Spanish
0.6	0.6286	0.5238	0.5714	0.5982	0.6
###Word2Vec_AverageVectors
Your Results
Language	Accuracy	Precision	Recall	F1 Binary	F1 Macro	F1 Micro
EN
English
0.6015	0.4286	0.1176	0.1846	0.4605	0.6015
SP
Spanish
0.497	0.5059	0.5119	0.5089	0.4967	0.497
###BagOfCentroids
Your Results
Language	Accuracy	Precision	Recall	F1 Binary	F1 Macro	F1 Micro
EN
English
0.7293	0.6744	0.5686	0.617	0.7039	0.7293
SP
Spanish
0.6667	0.6986	0.6071	0.6497	0.6659	0.6667

test
###Bag_of_Words_model
Your Results
Language	Accuracy	Precision	Recall	F1 Binary	F1 Macro	F1 Micro
EN
English
0.7149	0.6291	0.5441	0.5835	0.6834	0.7149
SP
Spanish
0.6465	0.6799	0.5374	0.6003	0.6417	0.6465
###Word2Vec_AverageVectors
Your Results
Language	Accuracy	Precision	Recall	F1 Binary	F1 Macro	F1 Micro
EN
English
0.6398	0.5439	0.1163	0.1917	0.48	0.6398
SP
Spanish
0.537	0.5364	0.4612	0.496	0.5339	0.537
###BagOfCentroids
Your Results
Language	Accuracy	Precision	Recall	F1 Binary	F1 Macro	F1 Micro
EN
English
0.7176	0.63	0.5591	0.5924	0.6882	0.7176
SP
Spanish
0.6815	0.7669	0.5102	0.6127	0.6711	0.6815

# development
# Subtask 2: Polarization Type Classification
### Multi-Label Classification Evaluation Results

Your Results
Language	F1 Micro	F1 Macro	Precision Micro	Precision Macro	Recall Micro	Recall Macro
EN
English
0.5714	0.3089	0.6786	0.3677	0.4935	0.2695
SP
Spanish
0.6573	0.642	0.6812	0.6589	0.6351	0.6296

# Subtask 3: Manifestation Identification
### Multi-Label Classification Evaluation Results

Your Results
Language	F1 Micro	F1 Macro	Precision Micro	Precision Macro	Recall Micro	Recall Macro	Exact Match
EN
English
0.4833	0.421	0.5909	0.5254	0.4088	0.3599	0.5414
SP
Spanish
0.5242	0.4364	0.5819	0.4726	0.4769	0.4122	0.4121

# test
# Subtask 2: Polarization Type Classification
### Multi-Label Classification Evaluation Results
Your Results
Language	F1 Micro	F1 Macro	Precision Micro	Precision Macro	Recall Micro	Recall Macro
EN
English
0.6031	0.3752	0.6396	0.5749	0.5705	0.3194
SP
Spanish
0.6451	0.6386	0.709	0.7009	0.5917	0.5915

# Subtask 3: Manifestation Identification
### Multi-Label Classification Evaluation Results
Your Results
Language	F1 Micro	F1 Macro	Precision Micro	Precision Macro	Recall Micro	Recall Macro	Exact Match
EN
English
0.4194	0.3561	0.4772	0.4475	0.374	0.321	0.5606
SP
Spanish
0.4902	0.4366	0.57	0.5297	0.43	0.3831	0.461
