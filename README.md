# Pocket Motion AI

A beginner engineering and AI project that uses a small neural network to classify motion patterns.

## Current results

The first model was trained on synthetic motion data with three classes:

- `0` — Still
- `1` — Shaking
- `2` — Circular motion

Test result:

- Test accuracy: approximately **90%**
- Test loss: approximately **0.77**

The test set contained 60 examples, so the model classified about 54 correctly.

## What I learned

- Python and NumPy arrays
- Creating and visualizing data with Matplotlib
- Splitting data into training and testing sets
- Building a neural network with TensorFlow/Keras
- Training and evaluating a classification model
- Uploading notebooks and data to GitHub
- Basic SolidWorks part design

## Project structure

```text
pocket-motion-ai/
├── notebooks/
│   └── pocket_motion_ai.ipynb
├── data/
│   └── synthetic_motion_data.csv
├── solidworks/
│   └── phone_holder.SLDPRT
└── README.md
```

## Tools used

- Python
- NumPy
- Matplotlib
- TensorFlow/Keras
- Google Colab
- GitHub
- SolidWorks

## Important note

The current model uses synthetic data for learning. It is not yet a reliable real-world phone-motion detector. The next improvement is to collect real accelerometer data and compare the neural network with a simple rule-based C++ classifier.

## Project status

First neural-network experiment completed. Real sensor-data collection and model improvement are planned next.
