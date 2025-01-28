
---

# Cognitive Load Detection

![GitHub](https://img.shields.io/github/license/Ayush-Tibrewal/CongnitiveLoad-Detection?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/Ayush-Tibrewal/CongnitiveLoad-Detection?style=social)

This project aims to detect cognitive load using various physiological and behavioral signals. Cognitive load refers to the total amount of mental effort being used in the working memory. Detecting cognitive load can have applications in education, healthcare, human-computer interaction, and more.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Cognitive load detection is a critical area of research in psychology and human-computer interaction. This project leverages machine learning and signal processing techniques to analyze physiological data (e.g., EEG, heart rate, eye-tracking) and behavioral data (e.g., keystrokes, mouse movements) to estimate cognitive load levels.

## Features

- **Multi-modal Data Analysis**: Combines physiological and behavioral data for robust cognitive load detection.
- **Machine Learning Models**: Implements state-of-the-art algorithms for classification and regression tasks.
- **Real-time Detection**: Capable of real-time cognitive load estimation (if applicable).
- **Visualization Tools**: Includes tools for visualizing data and model performance.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ayush-Tibrewal/CongnitiveLoad-Detection.git
   cd CongnitiveLoad-Detection
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the project**:
   Follow the instructions in the [Usage](#usage) section.

## Usage

To use this project, follow these steps:

1. **Prepare your dataset**:
   - Place your dataset in the `data/` directory.
   - Ensure the dataset is formatted correctly (refer to the [Dataset](#dataset) section).

2. **Preprocess the data**:
   - Run the preprocessing script:
     ```bash
     python scripts/preprocess.py
     ```

3. **Train the model**:
   - Train the model using the provided script:
     ```bash
     python scripts/train.py
     ```

4. **Evaluate the model**:
   - Evaluate the model's performance:
     ```bash
     python scripts/evaluate.py
     ```

5. **Visualize results**:
   - Generate visualizations of the results:
     ```bash
     python scripts/visualize.py
     ```

## Dataset

The dataset used in this project should include physiological and/or behavioral signals. Examples of such datasets include:

- **EEG data**: Brain activity recordings.
- **Heart rate data**: Pulse or heart rate variability.
- **Eye-tracking data**: Gaze patterns and pupil dilation.
- **Keystroke and mouse data**: Typing and mouse movement patterns.

Please ensure the dataset is properly formatted and placed in the `data/` directory. Refer to the `data/README.md` for more details.

## Methodology

This project employs the following steps:

1. **Data Collection**: Gather physiological and behavioral data.
2. **Preprocessing**: Clean and normalize the data.
3. **Feature Extraction**: Extract relevant features from the raw data.
4. **Model Training**: Train machine learning models using the extracted features.
5. **Evaluation**: Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.
6. **Visualization**: Visualize the results for better interpretation.

## Results

The results of the cognitive load detection models are summarized below:

- **Accuracy**: X%
- **Precision**: Y%
- **Recall**: Z%
- **F1-Score**: W%

For detailed results, refer to the `results/` directory.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

Please ensure your code follows the project's coding standards and includes appropriate documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Ayush Tibrewal**: Project creator and maintainer.
- **Contributors**: List of contributors (if any).
- **Open-source libraries**: Libraries and tools used in this project.

---

