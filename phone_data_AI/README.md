## Data

The project uses smartphone accelerometer recordings collected with the phyphox app.

The phone was recorded in three conditions:

- `still` — phone resting in the holder
- `shaking` — phone moved back and forth
- `circular` — phone moved in a circular motion

Each condition has two recordings:

- `*_train.csv` — used to train the neural network
- `*_test.csv` — kept separate for final testing

### CSV columns

Each file contains:

- `Time (s)`
- `Linear Acceleration x (m/s^2)`
- `Linear Acceleration y (m/s^2)`
- `Linear Acceleration z (m/s^2)`
- `Absolute acceleration (m/s^2)`

The files use comma-separated columns and decimal points.

### Feature extraction

The recordings are divided into one-second windows. From each window, the project calculates:

- Mean acceleration on the X, Y, and Z axes
- Standard deviation on the X, Y, and Z axes
- Mean absolute acceleration
- Standard deviation of absolute acceleration
- Maximum absolute acceleration

These features are used as inputs to the neural network.

### Data limitations

This is a small educational dataset collected from one phone and a limited number of motion trials. The model may not work equally well with another phone, another holder, or different movement styles.
