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

Create an environment with Python 3.6:  
>$ conda create --name myenv python=3.6  
_Replace "myenv" with the environment name of your choice_  

Activate the new environment:  
>$ conda activate myenv  

Install SpaCy:  
>_With conda:_  
$ conda install -c conda-forge spacy  
_With pip:_  
$ pip install -U spacy  

Download Spacy's English model:  
>$ python -m spacy download en_core_web_sm  

Install nltk:  
>_With conda:_  
$ conda install -c anaconda nltk  
_With pip:_  
$ pip install -U nltk  

Download all nltk packages:  
>$ python -m nltk.downloader all  

Install PDFminer3k:  
>_With conda:_  
$conda install -c conda-forge pdfminer3k  
_With pip:_  
$ pip install -U pdfminer3k  

**Usage**
1. Clone this repository onto your computer in any location
2. Inside the "Files" directory, create a sub-directory named "PDF"
3. Copy all of your PDF documents into "PDF"
4. Execute each cell from top to bottom

**NOTE:** All PDFs in the "PDF" directory will be processed by default. The process should not be stopped, so if you do not plan to leave your machine running, I recommend setting the _limit_ variable in freqMatrices to the number of documents you want to process before running that cell. _limit_ can also be set in pdfToText, although freqMatrices is the overarching time-consuming method. 
