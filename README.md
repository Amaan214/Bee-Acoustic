# Bee Acoustic Classification: Queen Presence Detection

## Overview

This project implements a machine learning pipeline to detect the presence of a queen bee in a colony using audio recordings. MFCC features are extracted from beehive sound clips, and a simple 1D Convolutional Neural Network (CNN) is trained to classify audio samples as either "queen present" or "queen absent." The notebook provides code, documentation, results, and references for full reproducibility.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [References](#references)

---

## Dataset

- **Source:** [Smart Bee Colony Monitor: Clips of Beehive Sounds](https://www.kaggle.com/datasets/annajyang/beehive-sounds?select=sound_files)
- **Author:** Anna Yang
- **DOI:** [10.34740/KAGGLE/DSV/4451415](https://doi.org/10.34740/KAGGLE/DSV/4451415)

---

## Requirements

Install dependencies using:
bash """
pip install -r requirements.txt
"""

**Core packages:**
- pandas
- numpy
- librosa
- tqdm
- scikit-learn
- tensorflow
- matplotlib
- seaborn

---

## Usage

1. **Download the dataset** from [Kaggle](https://www.kaggle.com/datasets/annajyang/beehive-sounds?select=sound_files) and extract it to the appropriate folder.
2. **Update the file paths** in the notebook if necessary.
3. **Run the notebook** `Bee_Acoustic_Classification.ipynb` from start to finish.
4. Results, plots, and metrics will be displayed in the output cells.

---

## Project Structure

├── Bee_Acoustic_Classification.ipynb # Main notebook
├── all_data_updated.csv # Metadata


---

## Results

- **Accuracy:** _[to be filled after running]_
- **Precision:** _[to be filled after running]_
- **Recall:** _[to be filled after running]_
- **F1-score:** _[to be filled after running]_
- **AU-ROC:** _[to be filled after running]_
- **AU-PRC:** _[to be filled after running]_

Plots include the confusion matrix and ROC curve, providing a visual summary of model performance.

---

## References

- **Dataset:**  
  Anna Yang. (2022). *Smart Bee Colony Monitor: Clips of Beehive Sounds*. Kaggle.  
  [Dataset Link](https://www.kaggle.com/datasets/annajyang/beehive-sounds?select=sound_files)  
  DOI: [10.34740/KAGGLE/DSV/4451415](https://doi.org/10.34740/KAGGLE/DSV/4451415)

- [Librosa documentation](https://librosa.org/doc/latest/index.html)
- [TensorFlow Keras Guides](https://www.tensorflow.org/guide/keras)

**BibTeX Citation:**
@misc{anna_yang_2022,
title={Smart Bee Colony Monitor: Clips of Beehive Sounds},
url={https://www.kaggle.com/dsv/4451415},
DOI={10.34740/KAGGLE/DSV/4451415},
publisher={Kaggle},
author={Anna Yang},
year={2022}
}
