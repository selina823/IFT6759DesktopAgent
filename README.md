# IFT6759DesktopAgent
Optimizing Final Exam Preparation with the Desktop Assistant Tool  The Desktop Assistant Tool is designed to facilitate an efficient and practical final exam preparation process. 
# Virtual Assistant for Educational Matching - Project README

## Overview
This project develops a virtual assistant using Jupyter notebooks that matches exam questions with course content. It utilizes data preprocessing, vector databases, and prompt-augmented generation with ChatGPT-3.5.

## Project Structure

### 1. Vector Database Integration
**Description:** Explains how to use the vector database to manage the preprocessed data.
- **Scripts/NBs**: `04_add_course.ipynb` and `05_exam_datapipeline.ipynb`
- **Instructions**: Follow the steps in this notebook to configure and populate the vector database. Detailed comments within the notebook guide the user through each step.

### 2. Using the Vector Database
**Description:** Details on how to interact with the vector database to retrieve and utilize stored vectors.
- **Scripts/NBs**: 
- **Instructions**: This notebook contains queries to fetch vectors from the database. Run cells sequentially to see how data retrieval is handled.

### 3. Prompt-Augmented Generation with ChatGPT-3.5
**Description:** Incorporates ChatGPT-3.5 to enhance data querying and matching. Techniques to match exam questions with course content.
- **Scripts/NBs**: 
- **Instructions**: Execute the notebook to generate prompts, send them to ChatGPT-3.5, and process the responses. Adjust the API keys and parameters as needed. Demonstrates the process of comparing vector representations to find matches between questions and content. Modify matching thresholds and criteria based on your needs.

### 4.Mind Map
**Description:** Generation of Mind Map
- **Scripts/NBs**: `data_matching.ipynb`
- **Instructions**: 

## Installation and Setup
Provide instructions for setting up the environment, including installing necessary packages and libraries:
```bash
pip install -r requirements.txt
```

## Usage
Detail the correct order to run the notebooks and what to expect from each output:

1) Run `04_add_course.ipynb` and `05_exam_datapipeline.ipynb` to prepare your data and etup the vector database.
2) Setup the vector database using
3) dsadfaerfaerg
4) aefaefragrg
