# OCR using KNN (K-Nearest Neighbors)

This project aims to develop an Optical Character Recognition (OCR) system using the K-Nearest Neighbors algorithm. The goal is to recognize characters from images and convert them into text.

## Project Description

The OCR system is based on the K-Nearest Neighbors algorithm, which is a simple and effective machine learning technique used for classification tasks. The system processes the provided training data, and then given an image with characters, it tries to recognize and classify the characters based on the K-Nearest Neighbors approach.

## Project Structure

The project folder contains the following directories and files:

- `samples/`: Directory containing sample images for testing the OCR system.

- `tests/`: Directory containing test scripts and test data.

- `train_data/`: Directory containing training data images.

- `cut_raw.py`: Python script for preprocessing raw images and extracting individual characters.

- `gen_data.py`: Python script to generate training data from preprocessed characters.

- `demo.py`: Python script for a demo of the OCR system on sample images.

- `recognize.py`: Python script to perform character recognition on given images.

- `ocr_knn.py`: The main OCR system implementation using the K-Nearest Neighbors algorithm.

## Getting Started

1. Clone the repository to your local machine using the following command:


2. Ensure you have Python installed on your system.

3. Install the required Python dependencies:
   ```
   pip install numpy opencv-python
   ```

4. Place the sample images you want to test in the `samples/` directory.

5. (Optional) If you have your own training data, place the preprocessed characters in the `train_data/` directory.

6. Run the demo script to see the OCR system in action:
   ```
   python demo.py
   ```

## Usage

The OCR system is designed to be flexible and expandable. You can use the provided `recognize.py` script to recognize characters from any given image. Simply provide the path to the image as an argument when running the script:
```
python recognize.py path/to/your/image.png
```
You can also modify and enhance the system as needed for your specific use case.
