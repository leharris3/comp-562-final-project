# Real-Time Wildfire Detection with MobileNet
***

## Overview
This project presents a real-time fire detection system developed for a machine learning class. We implement a fine-tuned MobileNet model, optimized for efficient on-device vision applications. We provide a lightweight yet accurate solution for identifying fires in real-time video feeds, which could be crucial for early fire detection and prevention measures.

## Features

- **Real-Time Detection**: Rapid identification of fire in video streams.
- **MobileNet Architecture**: Leverages the efficiency and speed of MobileNet.
- **Fine-Tuning for Fire Detection**: Specifically adapted to recognize various fire signatures.
- **Easy Integration**: Designed for straightforward implementation in various applications.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone [(https://github.com/leharris3/comp-562-final-project.git)]
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the application (see usage instructions below).

## Usage

To use the fire detection system, follow these instructions:

1. Activate the system with the provided script:
   ```
   python fire_detection.py
   ```
2. Adjust the settings in `config.py` for your specific use case (optional).

## Dataset and Training

The model was trained on a comprehensive dataset of fire and non-fire images, ensuring robust detection capabilities. The fine-tuning process involved adjusting the last few layers of the pre-trained MobileNet model to better suit fire detection tasks.

## Contributions

Contributions to this project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the machine learning instructors at the University of North Carolina at Chapel Hill for their guidance.
- The dataset providers for their valuable resources.
