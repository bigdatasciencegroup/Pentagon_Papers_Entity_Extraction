README for Pentagon_Paper_Data_Cleaning:  

Files in "Pentagon_Paper_Data_Cleaning": 
	- Txt_File_Cleaning.ipynb: takes in uncleaned files from Pentagon_Papers_Text_Files, decodes the encoding, exports the decoded files into folder 'Cleaned_Pentagon_Papers_text_files'.
	- Cleaned_File_Dataframe_Creation.ipynb: take in files that have been cleaned using 'Txt_File_Cleaning.ipynb'and have been further cleaned in Notepad++, creates a Pandas DataFrame table with supporting metadata about the files. The text column contains the full cleaned document. 
