## Overview
This project aims to conduct a comprehensive analysis of Optical Character Recognition (OCR) systems, specifically comparing the performance of Keras-OCR, Pytesseract, and EasyOCR algorithms on text extraction from images. The analysis will evaluate the accuracy, robustness, computational efficiency, scalability, and impact of preprocessing techniques on the OCR algorithms to provide actionable insights and recommendations for selecting the most suitable OCR solution based on specific use cases and requirements.

## Data Description
The TextOCR dataset is a collection of images sourced from various sources containing textual content. The dataset provides a diverse range of images with different text styles, fonts, sizes, orientations, and backgrounds to evaluate the performance of OCR algorithms under various conditions.

## Objectives
1. Evaluate the accuracy and robustness of Keras-OCR, Pytesseract, and EasyOCR in extracting textual content from images under various conditions.
2. Compare the computational efficiency and resource utilization of the OCR algorithms.
3. Assess the scalability of each OCR system by analyzing its performance across datasets of varying sizes and complexities.
4. Investigate the impact of preprocessing techniques on the OCR accuracy and reliability.
5. Explore the potential limitations and failure modes of each OCR system.

## Outcome
The project will result in a comprehensive analysis report detailing the comparative evaluation of Keras-OCR, Pytesseract, and EasyOCR algorithms for text extraction from images. The report will include actionable recommendations for selecting the most appropriate OCR solution for various practical applications.

## Repository Structure
- **Output:** Contains the TextOCR dataset's analysed Images that has the labels.
- **Notebooks:** Jupyter notebooks detailing the analysis process and results.
- **README.md:** Overview of the project, objectives, methodology, and key findings.

## Usage
To replicate the analysis, follow these steps:
1. Download the TextOCR dataset from [Kaggle](https://www.kaggle.com/datasets/robikscube/textocr-text-extraction-from-images-dataset/data) .
2. Install the required libraries (Keras-OCR, Pytesseract, EasyOCR).
3. Run the analysis scripts in the provided notebooks.

## Acknowledgements
We would like to thank the creators of Keras-OCR, Pytesseract, and EasyOCR for their valuable contributions to the field of Optical Character Recognition.

## Dataset
@inproceedings{singh2021textocr,
    title={{TextOCR}: Towards large-scale end-to-end reasoning for arbitrary-shaped scene text},
    author={Singh, Amanpreet and Pang, Guan and Toh, Mandy and Huang, Jing and Galuba, Wojciech and Hassner, Tal},
    journal={The Conference on Computer Vision and Pattern Recognition},
    year={2021}
}

Thank you
