# AP1 Transcription Factor Binding Site Prediction

In this project, we built machine learning models to predict and classify the binding sites of AP1 transcription factor in the human genome. 

Experiments such as Chip-Seq can identify a list of DNA regions bound by a given transcription factor. Combined with a computational scan for the AP1’s position- weight matrix, this can be used to identify sites that are occupied by AP1 in the cell type and conditions where the experiments were made. 

The project involved:
(1) Identifying a set of bound and non-bound DNA sequences for a given TF based on existing experimental data
(2) Calculating the DNA physical properties of each sequence
(3) Training a machine learning classifier to distinguish between bound and unbound sites.

With the use of **sequencePreProcessing.py** and **motifPreProccessing.py**, we pre-proccessed the local DNA shape and motif sequence data.

In **machineLearningClassifers.py**, we built and trained the classifers using this dataset.

In **Using Machine Learning to Predict AP1 TF Binding Sites.pdf**, we shared our results and analysis of the project. 
