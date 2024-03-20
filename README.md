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

### LLM used :  facebook/m2m100_418M

### Result 

#### model :   facebook/m2m100_418M 
#### model size :   1.94 GB
#### [ex./sec.]	runtime performance :  0.35 
#### title only [ex./sec.] : 	 1.94
