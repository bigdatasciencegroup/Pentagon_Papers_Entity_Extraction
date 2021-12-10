# Pentagon_Papers_Entity_Extraction
--------------------------
A natural language processing project that analyzes the U.S. government documents "Pentagon Papers" and runs entity analysis on them.  
Author/Project Creator: Lauren Phegley  
Contact: lphegley5@gmail.com  
Date of Creation: 2021/11/01  
Suggested Citation: Phegley, L. (2021). Pentagon Paper Entity Extraction. 

--------------
NOTICE: The Pentagon Papers are the works of the U.S. Government and in the public domain.  
Code License:  MIT License
Data License: CC0 1.0 License

----------- 
## Data: 
You can access the original Pentagon Paper PDFs at the National Archives: <https://www.archives.gov/research/pentagon-papers>. Please note that the National Archives files are photocopies of the documents, and have not been OCR'd. I have made fully avaliable the OCR'd Pentagon Paper's Text Files, which I estimate to be about 60-80% correct. 
I used ABBYFineReader (through my University Library) to complete the OCR using the pattern recognition. The documents are not perfect, but it hopefully is better than starting from scratch. 

-----------
## TOP LEVEL FILE ORGANIZATION & DESCRIPTION: 
"Pentagon_Papers_Entity_Extraction":  
- "Cleaned_Pentagon_Papers_text_files": These text files are text files that have been cleaned by decoding their ascii and then using Notepad++'s Replace function.  
- "Entity_Extraction": Code to run entity extraction on the cleaned text files and create dataframe from it.  
- "Pentagon_Paper_Data_Cleaning": Files related to cleaning the text files and creating a Pandas dataframe  
- "Pentagon_Paper_Text_Files": text files that are directly taken from the OCR'd Pentagon Papers. These are not cleaned, but are avaliable so you can make decisions as to how to what information to remove or clean for your research. 
  
------------
## Software Used - Version: 

Jupyter Notebook - 6.3.0  
python - 3.8.8

## Python Packages/Libraries:  
en_core_web_sm - 3.1.0  
numpy - 1.20.1  
pandas - 1.2.4  
spacy - 3.1.3
