# Fact-Checking-Engine
[Project Overview](#project-overview)  | [Installation](#installation)   | [Techniques](#techniques) | [Contribution](#contribution)

## Project Overview
A Knowledge Graph Fact Verification System - This system determines the truthfulness of RDF statements using path-based features and ensemble machine learning. Here's how it works:

Core Components

**Knowledge Graph Processing**
* Takes a reference knowledge graph containing 675,859 triples
* Removes literal values to keep only URI relationships, resulting in 660,000 triples1
* Uses these relationships to find paths between entities
**Path Discovery**
* For each subject-object pair, finds connecting paths up to length 3
* Generates SPARQL query templates dynamically
* Excludes basic RDF predicates (subClassOf, range, domain, type)
* Counts frequency of unique paths between entities

## Installation

- pip install -r requirements.txt
- You will need Jupyter Notebook
- Just Run the file main.ipynb

## Techniques
Ensemble model
An algorithm that aims to validate facts by utilizing information from a knowledge graph and using RandomForest, LogisticRegression and KNN to predict.

## Contribution:

| Name                  | Matriculation Number |
| --------------------- | -------------------- |
| Amal Nimmy Lal   |   6987112            |
| Aryman Deshwal   |  4011205           |
