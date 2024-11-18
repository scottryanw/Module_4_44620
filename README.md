# Requests, JSON, and basic NLP with spaCy

Completed Jupyter Notebook for Module 4 of Web Mining and Applied NLP (44-620). All cells and tasks edidted by Scott Williamson for this assignment. Assignment shows use of Natural Language Processing and one particular application: Sentiment Analysis.

## Create virtual environment
'''bash
python3 -m venv .venv
source .venv/bin/activate
'''

## Git add and commit 
'''bash
git add .
git commit -m "comment"
git push -u origin main
'''

## Install Dependencies
'''bash
python3 -m pip install requests spacy spacytextblob jupyterlab numpy pandas matplotlib seaborn scipy
python3 -m pip freeze > requirements.txt
'''

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts
