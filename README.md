# tweet-hate-speech-recognition
EVALITA 2023 challange 
Dataset and its description on http://www.di.unito.it/~tutreeb/haspeede-evalita23/index.html (Does not work with Microsoft Edge)


Elements contained:

	- Project Report
	- Data:
  		- development
  		- gold
  		- test
  		- df_preprocessed.csv
    
	- Notebooks:
		- 1_TXA_ DataUnderstanding&Preprocessing.ipynb
		- 2_TXA_Topic_Modeling.ipynb
		- 3_TXA_classification
		- 4_TXA_LSTM_and_CNN.ipynb
		- 5_TXA_BERT.ipynb


- development, gold and test are folders containing the source data used as input in '1_TXA_ DataUnderstanding&Preprocessing'.

- df_preprocessed.csv is the output file of "1_TXA_ DataUnderstanding&Preprocessing", used as input to run all other notebooks. 

- The notebooks, already compiled and with visible output, were executed in the same order in which they are numbered.
  In particular, the **\3_TXA_classification** folder contains a different notebook for each classifier used, with the execution structure remaining the same. 
	- loading data from preprocessed.csv file
	- test classification without pipeline/grid search on clean_text column
	- use pipeline and grid search to optimise the classifier 
	- target balancing tests on best classifier configuration 
	- plot results
	- performance increase test with metadata

   
