The description of the files in the folder:
1. Report_assign_3 - Report of the assignment
2. Seq2Seq + Simple - Simple version 
	+ attention - Attention model with visualisations
	+ Removed SOS tags - Model performance when the EOS/SOS tags are removed
	+ No_TFor. - Model without Teacher Forcing.

The data used for this part is downloaded from the link "https://download.pytorch.org/tutorial/data.zip"

3. Seq2Seq_beam_search + length10 - When the max_sentence_length is 10
			+ length30 - When the max_sentence_length is 30 
			+ final_length50 - When the max_sentence_length is 50

The data used for this model is downloaded from link "https://wit3.fbk.eu/download.php?
release=2014-01&type=texts&slang=en&tlang=fr"

4. Seq2Seq_beam_search + mixed_data - Model is trained on 1st dataset and predictions are made on the 2nd dataset. 
			    