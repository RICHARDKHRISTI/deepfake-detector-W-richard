# Deepfake Detection with Python

This project demonstrates how to detect deepfake videos using frame-by-frame analysis. It extracts frames from two input videos (real and fake), compares them using Mean Squared Error (MSE) and Structural Similarity Index (SSIM), and visualizes the differences.

## Features

- Extracts frames from videos using OpenCV
- Compares selected frames using MSE and SSIM
- Displays and saves visual side-by-side results
- Includes error handling for mismatched resolutions

## Technologies

- Python
- OpenCV
- scikit-image
- MTCNN (optional for future face detection)
- Google Colab

## Results

![Comparison Output] [https://github.com/RICHARDKHRISTI/deepfake-detector-W-richard/blob/6583a1c6b58a143bb84ab0f47667378d6eee6196/imagescomparisonoutput.png]

## How to Use

1. Upload two videos (`real.mp4` and `fake.mp4`) to your environment.
2. Run the notebook `deepfake_detector.ipynb`.
3. Use the provided functions to extract frames and compare them.
4. View the visual differences between frames.

## Credits

Built by Richard Khristi – July 2025  
GitHub: [https://github.com/RICHARDKHRISTI]
