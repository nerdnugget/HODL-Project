# HODL-Project

# Predicting Legislative Bill Passage in North Carolina

## Project Overview

This deep learning project aims to predict the likelihood of legislative bill passage in North Carolina using advanced machine learning techniques. Developed as part of a 15.773 course project (due March 16, 2025), the model leverages comprehensive legislative data to provide insights into bill success probabilities.

## Project Notebook

### Google Colab
You can access the full project notebook directly in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BA3cWiK3PLluvD0UC-GQ_hDSQjjfRGWH?usp=sharing)

### Local Notebook
The project notebook is also available in the repository as `HODL_Final_Project_Sunday.ipynb`

## Project Motivation

Legislators introduce thousands of draft bills each year, but only a fraction become law. This project seeks to:
- Provide a data-driven tool for policymakers
- Enhance legislative transparency
- Help prioritize legislative efforts

## Methodology

### Data Sources
- North Carolina General Assembly (NCGA) data
- LegiScan dataset
- University of North Carolina (UNC) compilation

**Important**: The main dataset file `data/hodl data final.csv` is required to run the analysis. This file is stored using Git LFS due to its size. When using Google Colab, make sure to:
1. Download this file from the repository
2. Upload it to your Colab runtime in the specified location
3. Verify the data path in the notebook matches the uploaded location

### Key Features
- Bill metadata analysis
- Sponsorship patterns
- Voting records
- Natural Language Processing (NLP) of bill summaries
- Deep Neural Network (DNN) modeling

## Model Performance

SMOTE-Balanced Model:

AUC Scores: 0.78 - 0.81
Overall Accuracy: 71% - 75%

## Key Insights

### Factors Influencing Bill Passage
- Sponsorship patterns
- Bipartisan support
- Policy area relevance
- Political party affiliation
- Chamber of origin

## Technical Approach

- **Data Cleaning**: Rigorous preprocessing
- **Feature Engineering**: 
  - Categorical variable conversion
  - NLP-based topic scoring
  - Sponsor ratio calculations
- **Balancing Techniques**: 
  - SMOTE (Synthetic Minority Over-sampling Technique)
  - Class weighting

## Repository Structure

- `HODL_Final_Project_Sunday.ipynb`: Main project notebook
- `data/`: Raw and processed datasets
- `models/`: Saved model artifacts
- `docs/`: Project documentation

## Prerequisites

- Python 3.8+
- Google Colab (recommended)
- Required libraries: 
  - TensorFlow
  - Pandas
  - Scikit-learn
  - Numpy

## How to Use

1. **Recommended**: Open in Google Colab
   - Click the Colab badge above
   - Make a copy of the notebook
   - Run the cells

2. **Local Usage**:
   - Clone the repository
   - Open the notebook in Jupyter or Google Colab
   - Install required dependencies

## Future Improvements

- Incorporate real-time legislative developments
- Enhance NLP feature extraction
- Add external political context
- Explore advanced deep learning techniques

## References
- LegiScan API
- North Carolina General Assembly
- University of North Carolina legislative datasets

## License
MIT License

Copyright (c) 2025 Course Project Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

**Note**: This model is a research tool developed for course purposes. 
