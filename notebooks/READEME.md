# Pocket Motion AI Notebook

This notebook demonstrates a beginner neural-network classification project using synthetic motion data.

## What the notebook does

1. Imports NumPy, Matplotlib, and TensorFlow.
2. Creates synthetic data for three motion classes:
   - `0` — Still
   - `1` — Shaking
   - `2` — Circular motion
3. Visualizes the data as a scatter plot.
4. Shuffles and splits the data into training and testing sets.
5. Builds a small TensorFlow/Keras neural network.
6. Trains the model for 30 epochs.
7. Evaluates the model on previously unseen test data.

## Result

The current model achieved approximately:

- Test accuracy: **90%**
- Test loss: **0.77**

The data is synthetic and created for learning. It does not yet represent real smartphone sensor measurements.

## How to run

Open the notebook in Google Colab and run the cells from top to bottom. Each section depends on variables created by earlier sections.

## Next steps

- Collect real accelerometer data.
- Replace the synthetic features with real sensor features.
- Display a confusion matrix.
- Compare the neural network with a simple rule-based classifier.
