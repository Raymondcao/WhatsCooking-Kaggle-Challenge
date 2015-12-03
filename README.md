# WhatsCooking-Kaggle-Challenge        
        
DATA PRE-PROCESSING USAGE:        
$python BuildExcludeList.py        
	input:	adjectives.json     adjective word list generated using nltk from all ingredients        
			ed-words.json     list of words that ended with 'ed'        
			train.json      training dataset downloaded from kaggle.com        
			test.json      test dataset from kaggle.com        
	output: excludeList.json       list of words that have no significant meanings to train model or to predict           
        
$python ExcludeWordsFromFile.py filename.json        
	input:	filename.json      training or testing dataset that needs to be preprocessed        
			excludeList.json      list of words that need to exclude from ingredient string        
	output:	prepared_filename.json      dataset in the same format as training or testing        
