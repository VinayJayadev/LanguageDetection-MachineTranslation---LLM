# Machine-Translation---LLM
Language detection and translation using Large Language models

### Goal : 
•	machine translate the titles and abstracts of the example documents into English for documents with unknown language code
•	Measure inference runtime and performance (examples per second)


### Prequisites
- !pip install transformers --quiet
- !pip install sentencepiece --quiet 
- !pip install pandas --quiet 
- !pip install langcodes  --quiet 
- !pip install langdetect --quiet 
- !pip install nltk --quiet 
- !pip install fasttext-langdetect --quiet 

### LLM used : #### facebook/m2m100_418M

### Result 
#### model                  [ex./sec.]	  runtime performance   title only [ex./sec.]
#### facebook/m2m100_418M     	1.94 GB	         0.35              	1.94
