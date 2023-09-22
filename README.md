# Blindness Detection

## Overview

Millions of people suffer from diabetic retinopathy, the leading cause of blindness among working-aged adults. This project aims to address this issue by developing a machine learning model that can automatically detect and classify diabetic retinopathy in retinal images. The project is a part of the 4th Asia Pacific Tele-Ophthalmology Society (APTOS) Symposium and is in collaboration with Aravind Eye Hospital in India.


## Background

Aravind Eye Hospital currently relies on manual diagnosis of diabetic retinopathy by highly trained doctors. The goal of this project is to automate this process using machine learning. Successful implementation will significantly improve the hospital's ability to identify potential patients, thus preventing blindness.

## Dataset

### Description

The dataset consists of retinal images captured under various conditions, each rated for the severity of diabetic retinopathy on a scale of 0 to 4, where:
- 0 - No DR
- 1 - Mild
- 2 - Moderate
- 3 - Severe
- 4 - Proliferative DR

### Files

- `train.csv`: Training labels
- `test.csv`: Test set (for making predictions)
- `sample_submission.csv`: Sample submission file
- `train.zip`: Training set images
- `test.zip`: Test set images

## Getting Started

Follow these steps to get started with the project:

1. Clone this repository to your local machine.
2. Extract the contents of `train.zip` and `test.zip` for image data.
3. Use `train.csv` for training data and labels.
4. Create and train your machine learning models.
5. Make predictions on the test set using your trained model.
6. Ensure your predictions are in the format specified in `sample_submission.csv`.
7. Submit your predictions to the competition platform.

