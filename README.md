# Text-Retrieval
This project focuses on building a data retrieval system for Persian language text mining. It involves loading, preprocessing, and analyzing a dataset of 1000 Persian news articles to implement and evaluate different information retrieval models, including boolean and vector space models.

## Table of Contents
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Information Retrieval Models](#information-retrieval-models)
- [Installation](#installation)
- [Usage](#usage)
- [Queries and Results](#queries-and-results)
- [Contributors](#contributors)

## Dataset

The dataset consists of Persian news articles collected for text mining purposes. It's split into multiple parts due to its size and needs to be extracted after cloning the repository.

```bash
git clone https://github.com/Text-Mining/Useful-Corpora-for-Text-Mining-in-Persian-Language.git
unrar x '/content/Useful-Corpora-for-Text-Mining-in-Persian-Language/News/FarsNews 97/farsnews.part01.rar'
```

## Preprocessing

The preprocessing pipeline includes normalization, tokenization, stemming, and stop words removal using the Hazm library. This prepares the data for efficient retrieval by reducing it to its essential components.

## Information Retrieval Models

We implement both boolean and vector space models to retrieve information from the processed dataset. The boolean model simplifies document querying through logical operations, while the vector space model allows for more nuanced query responses based on document and query vector representations.

## Installation

To run this project, you'll need to install certain Python libraries, primarily Hazm for text preprocessing in Persian.

```bash
pip install hazm
```
## Usage

The project is structured as a series of Jupyter notebooks that guide you through the process of data loading, preprocessing, and applying information retrieval models. To start, open the Data_Loading_and_Preprocessing.ipynb and follow the instructions within.

## Queries and Results

We include a set of predefined queries to demonstrate the functionality of the implemented models. Results of these queries highlight the models' effectiveness in retrieving relevant documents from the dataset.

## Contributors
Helia Ghahraman , Minoo Mohaghegh
