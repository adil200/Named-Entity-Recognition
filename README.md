
# Named Entity Recognition (NER) on Airline Reviews

Welcome to the "Named Entity Recognition (NER) on Airline Reviews" project! This repository focuses on performing Named Entity Recognition on a dataset of airline reviews using the spaCy library.

## Overview

In this repository, you will find a Jupyter Notebook (`named-entity-recognition.ipynb`) that demonstrates how to perform Named Entity Recognition on airline reviews using spaCy's pre-trained model. The notebook loads the `Airline_Reviews.csv` dataset, processes each review, and extracts named entities along with their labels. It also provides visualizations of the named entities using displaCy.

## Installation

To run the code in the notebook, you'll need the following dependencies:

-   Python 3
-   pandas
-   spaCy
-   en_core_web_sm (spaCy's pre-trained model for English)

You can install these dependencies using the following command:

```bash
pip install pandas spacy
python -m spacy download en_core_web_sm
```
## Usage

1.  Clone this repository:

```bash
git clone https://github.com/adil200/Named-Entity-Recognition.git
```
2.  Download the dataset (`Airline_Reviews.csv`) and place it in the project's root directory.
    
3.  Launch Jupyter Notebook and open the `named-entity-recognition.ipynb` notebook.
    
4.  Follow the instructions in the notebook to explore Named Entity Recognition on airline reviews and visualize the extracted entities.
    

## Results

After processing the reviews and extracting named entities, you can observe the top 10 most common named entities and their frequencies:

-   Entity: first - Frequency: 733
-   Entity: one - Frequency: 502
-   Entity: 2 - Frequency: 454
-   Entity: two - Frequency: 358
-   Entity: 3 - Frequency: 315
-   Entity: London - Frequency: 242
-   Entity: First - Frequency: 222
-   Entity: Paris - Frequency: 214
-   Entity: second - Frequency: 209
-   Entity: Beijing - Frequency: 202

## Acknowledgments

Various tutorials and resources on Named Entity Recognition and spaCy inspire the code and techniques used in this project.
