# Meeting_ICH_24Mar2020

Ferrán González Hernández on Biomedical Natural Language Processing: Applications and Software

***Abstract***

With a growing volume of biomedical information reported in textual format, Natural Language Processing (NLP) has become an essential technique to efficiently extract, integrate and exploit knowledge stored across extensive collections of unstructured text. From rule-based to machine learning approaches, this presentation will introduce the main concepts, methodology, and software behind NLP and discuss its potential applications in biomedical research.

This meeting is virtual - it will take place on MS Teams, look for the group ICH Coding Club.


# Running instructions for jupyter notebooks: 

0. Clone this repository in your local machine and access the directory through the following bash commands:

````
git clone https://github.com/UCLichCodeClub/Meeting_ICH_25Mar2020
cd Meeting_ICH_25Mar2020
````

1. Install python 3 and anaconda. Make sure "pip" (or pip3)runs python 3 in bash terminal

https://www.python.org/downloads/
https://www.anaconda.com/distribution/



2. Install dependencies

````
pip install -r requirements.txt
pip install https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.2.4/en_ner_bc5cdr_md-0.2.4.tar.gz
````

3. Launch jupyter from Meeting_ICH_25Mar2020 repository:

````
jupyter notebook 
````

This should open a local host from which you can access and run the notebooks

4. For running DocClassification.ipynb you will need to download and extract this data on the Meeting_ICH_25Mar2020 directory: 

http://www.cs.cornell.edu/people/pabo/movie-review-data/review_polarity.tar.gz
