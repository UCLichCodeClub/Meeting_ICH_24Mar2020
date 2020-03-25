# Meeting_ICH_24Mar2020

Ferrán González Hernández on Biomedical Natural Language Processing: Applications and Software

***Abstract***

With a growing volume of biomedical information reported in textual format, Natural Language Processing (NLP) has become an essential technique to efficiently extract, integrate and exploit knowledge stored across extensive collections of unstructured text. From rule-based to machine learning approaches, this presentation will introduce the main concepts, methodology, and software behind NLP and discuss its potential applications in biomedical research.

This meeting is virtual - it will take place on MS Teams, look for the group ICH Coding Club.

# Running instructions for jupyter notebooks: 

0. Clone this repository in your local machine and access the directory

````
git clone https://github.com/UCLichCodeClub/Meeting_ICH_25Mar2020
cd Meeting_ICH_25Mar2020
````

1. Install conda and make sure you can run it from terminal. See details: https://docs.conda.io/projects/conda/en/latest/user-guide/install/

2. Make new environment by running the following on a bash shell:

````
conda create -n nlptutorial python=3.7
````

3. Activate environment

````
conda activate nlptutorial 
````

4. Launch jupyter and open the desired notebook

````
juputer notebook
````

5. For running DocClassification.ipynb you will need to download this data on the same working directory: 

http://www.cs.cornell.edu/people/pabo/movie-review-data/review_polarity.tar.gz
