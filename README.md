The file evaluation_script.py requires two files. 
The first file should contain the gold standard translations and the latter should contain the predictions made by your model, each translation in one line. 
Each line in prediction file should be corresponding to the respective line in order in the reference file. The script will output the average BLEU and METEOR scores for your model. 
The range of BLEU and METEOR scores are both 0 to 1.
Command to run evaluation script: python3 evaluation_script.py reference_file prediction_file
