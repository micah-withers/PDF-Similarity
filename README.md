PDF Cosine Similarity
===

A system for calculating the similarity of PDF documents in a directory
---

**Requirements**
* Anaconda
* Python 3.6
* SpaCy
* NLTK
* PDFminer3k

**Installation**  
Open terminal or an Anaconda Prompt  

To create an environment with Python 3.6:  
>$ conda create --name myenv python=3.6  
_Replace "myenv" with the environment name of your choice_  

To activate the new environment:  
>$ conda activate myenv  

To install SpaCy:  
>_With conda:_  
$ conda install -c conda-forge spacy  
_With pip:_  
$ pip install -U spacy  

To download Spacy's English model:  
>$ python -m spacy download en_core_web_sm  

To install nltk:  
>_With conda:_  
$ conda install -c anaconda nltk  
_With pip:_  
$ pip install -U nltk  

To download all nltk packages:  
>$ python -m nltk.downloader all  

To install PDFminer3k:  
>_With conda:_  
$conda install -c conda-forge pdfminer3k  
_With pip:_  
$ pip install -U pdfminer3k  

**Usage**
1. Clone this repository onto your computer in any location
2. Create a new directory named "Files" in a location of your choice
3. Inside the directory, create a sub-directory named "PDF"
4. Copy all of your PDF documents into "PDF"
5. 
