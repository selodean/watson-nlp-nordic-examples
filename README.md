# Watson NLP example notebooks to run in Watson Studio

## 1. Language: Multi-lingual

'**Syntax-Entities-Keywords-Sentiment-Multilingual.ipynb**' is a very simple starter notebook that loads and runs pre-trained models included in Watson NLP: Syntax, machine-learned and rule-based Entities, Sentiment and Keywords. Simply change text_input and language code to your favorite language.

## 2. Language: Finnish (FI)

2 Python notebooks and 2 datasets to run Watson NLP library models on Finnish text in Watson Studio. They can be easily adapted to another language by changing a) the data set b) the language code in the names of the loaded libraries.

'**Citizen-Feedback-Analysis-FI.ipynb**' analyses and visualizes Sentiment and Entities using as data source '**helsinki-feedback-data.csv**', trains a Dictionary based extractor. 

(This notebook is a Finnish adaptation of the English language 'Financial Complaint Analysis' notebook available in the 'Using Watson NLP in Watson Studio' Sample Project in Watson Studio authored by Simone Zerfass and Alexander Lang at IBM Germany)

'**Classifier-training-BERT-SVM-FI.ipynb**' executes SVM and BERT classifier training using as data source '**helsinki-raw-data_with_3classes_small.csv**'
You will likely need an environment with more than 4 vCPUs and 16 GB RAM, or GPU due to BERT model training requirements. I ran this with 16 vCPUs and 64 GB RAM.

(This notebook is a Finnish adaptation of the English language 'Complaint Classification' notebook available 'Using Watson NLP in Watson Studio' Sample Project in Watson Studio authored by Simone Zerfass and Alexander Lang at IBM Germany)

The datasets consist of open data of Helsinki City feedback data downloaded from http://dev.hel.fi/apis/open311

-----------------------------------------------------

## Code disclaimer information 

This repo contains programming examples.

IBM grants you a nonexclusive copyright license to use all programming code examples from which you can generate similar function tailored to your own specific needs.

All sample code is provided by IBM for illustrative purposes only. These examples have not been thoroughly tested under all conditions. IBM, therefore, cannot guarantee or imply reliability, serviceability, or function of these programs.

All programs contained herein are provided to you "AS IS" without any warranties of any kind. The implied warranties of non-infringement, merchantability and fitness for a particular purpose are expressly disclaimed.
