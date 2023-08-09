# OCR for Medical Imaging Project

This project implements an Optical Character Recognition (OCR) solution to process medical images. The goal is to extract and convert the text content from these images into usable text.

## Environment Setup

Before getting started, ensure you have the following dependencies installed:
- Python 
- OpenCV (cv2)
- Numpy
- Matplotlib
- Pillow (PIL)
- PyTesseract
- NLTK
- Scikit-learn

## Features

The project includes the following features:

1. **Preprocessing and Text Extraction from Medical Images**:
   - Use functions `preproces_extract_img_1`, `preproces_extract_img_2`, `preproces_extract_img_3`, and `preproces_extract_img_4` to apply different image processing techniques and extract text.

2. **Metric Calculation for OCR Evaluation**:
   - Utilize the `calcul_metric` function to compute various metrics such as Levenshtein distance, Jaccard coefficient, Dice similarity, and cosine similarity between the obtained OCR results and reference texts.

3. **Result Generation and Visualizations**:
   - Extracted text is saved in text files for each processed image.
   - Generated plots compare different metrics across image processing configurations.

## Usage

1. Clone this repository to your local machine.
2. Ensure you install the listed dependencies in the environment.
3. Use `preproces_extract_img_x` functions to extract text from images. Customize configurations based on your requirements.
4. Use the `calcul_metric` function to evaluate OCR performance.
5. Run the scripts to generate results and visualizations.

## Execution Example

```bash
python main.py
