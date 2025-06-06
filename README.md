# KeywordSpotting
Keyword Spotting with CNN for Game Control This project implements a lightweight convolutional neural network (CNN) trained to detect voice keywords using MFCC features and data augmentation (e.g., background noise). The model is deployed to control a Snake game using voice commands. It runs on both desktop and Raspberry Pi devices.

## Project Overview

  (The sources here only implement the final result, but if you are interested in the process of getting there you can take a look at the internship report that explains everything)

- **Training Notebook:** `CNNoisySilence.ipynb`
  - MFCC preprocessing
  - Data augmentation (e.g., adding noise)
  - CNN model training and saving
- **Deployment Notebook:** `modelLoadRas.ipynb`
  - Load the trained model
  - Detect real-time voice commands
  - Use commands to control the Snake game

## Features

- MFCC-based audio feature extraction
- Data augmentation with background noise
- Lightweight CNN model for real-time inference
- Real-time voice interaction with a Python-based Snake game
- Portable deployment tested on Raspberry Pi

## Repository Contents

| File/Folder               | Description |
|---------------------------|-------------|
| `source/CNNoisySilence.ipynb`    | Training notebook with preprocessing and CNN |
| `source/modelLoadRas.ipynb`      | Model loading and voice interaction with the game |
| `InternshipReportBENAISSAv1.pdf` | Internship report (M1) detailing the project |
| `videos/`                 | Demo videos : KWS on Raspberry Pi : https://youtu.be/E9Up6s6eMeE , Snake on Raspberry Pi : https://youtu.be/i-FqUyaQLY8 , Snake on PC : https://youtu.be/3D71_armeyg |

## Getting Started

### Prerequisites

- Python 3.7+
- Recommended libraries:
  - `torch`
  - `librosa`
  - `numpy`
  - `matplotlib`
  - `pygame`
  - `PvRecorder`


