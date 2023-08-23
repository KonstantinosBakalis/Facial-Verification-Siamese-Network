# Facial Verification with a Siamese Network

## Project description
This facial verification app utilizes a Siamese network to verify images against an anchor image. Developed in Google Colab and employing TensorFlow, Keras, OpenCV-Python, Matplotlib, and tqdm, the app builds on the innovative methodology outlined in a scientific paper.

## Key Components

### 1. Automatic Creation of Folder Structures
A well-organized folder structure is automatically generated to streamline the handling of different data types, including positive images, negative images, and anchor images.

### 2. Download and Uncompress Negative Images
Automatically downloaded and uncompressed from [UMass LFW dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).

### 3. Javascript for Collecting Positives and Anchors
Collects 400 images comprising positives and anchors.

### 4. Data Augmentation
Techniques are applied to amplify the initial collection ninefold.

### 5. Load and Preprocess Images
Images are preprocessed using OpenCV-Python and other tools.

### 6. Model Engineering as Specified in the Paper
Follows the specific guidelines in the referenced [Siamese Neural Networks for One-shot Image Recognition paper](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf).

### 7. Training with Binary Cross-Entropy and Adam Optimizer
Training conducted using the binary cross-entropy loss function and the Adam optimizer.

### 8. Precision, Recall, and Visual Results
Metrics include loss, recall, and precision.

### 9. Saving Model
The trained model is saved securely.

### 10. Building a Python App in Visual Studio Code
The Python app integrates the trained model, offering a user-friendly interface for real-world facial verification. Users can capture images through a webcam interface, and the app processes the image through the trained Siamese network for facial verification.

### 11. Improvement Suggestions
Based on the metrics observed, future improvements could focus on refining the data augmentation strategies, exploring different loss functions, and optimizing hyperparameters. Continuous model evaluation and potential integration of additional datasets might contribute to higher performance and robustness.

## License
This project is licensed under the CC0 1.0 Universal - see the [LICENSE.md](LICENSE.md) file for details.
