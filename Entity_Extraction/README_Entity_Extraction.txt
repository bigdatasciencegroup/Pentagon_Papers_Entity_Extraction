README for Entity_Extraction 

Files in 'Entity_Extraction': 
	- Entity_Extraction_Pentagon_papers_V04.ipynb: code that does entity extraction using spaCy on the individual documents to pull out certain aspects of the documents. This entity extraction currently looks at organizations and people.  
	- full_txt_document.csv: a helpful csv that provides document metadata and the full cleaned text document. 



full_txt_document dictionary: 

*note* - I would suggest looking at the PDF Index for a good visual representation of the Pentagon Paper volume organization. Most of this information was taken from that document.

name: the unofficial title it is given based on the numbering system of the files.  
title: the most granular title that could be given to the document. Some of the titles are a combination of different hierarchical headings to clarify what the title. 
overall_years: the years the document covers. Most of this was found in the Index, although some were not given dates so the information was found within the document, usually in the Chronology section.
specific_dates: some of the documents covered times that were smaller than a year, so this allows for more granular information. If the document operated in years, the specific_date and overall_years should be the same. The date format is either mm/yyyy - mm/yyyy or mm/dd/yyyy-mm/dd/yyyy.
text: the entirity of the cleaned text document 