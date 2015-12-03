# WhatsCooking-Kaggle-Challenge

DATA PRE-PROCESSING USAGE:
$python BuildExcludeList.py
  input:  adjectives.json
          ed-words.json
          train.json
          test.json
  output: excludeList.json          
        
$python ExcludeWordsFromFile.py filename.json
  input:  filename.json
          excludeList.json
  output: prepared_filename.json
