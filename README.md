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

