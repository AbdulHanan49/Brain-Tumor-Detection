# Brain Tumor Detection - Image Preprocessing & Visualization

## Overview
This project focuses on loading, preprocessing, and visualizing brain tumor images. The dataset consists of two categories: **Tumor Images** and **Non-Tumor Images**. The code reads images from specified directories, processes them, and displays a sample set for analysis.

## Features Implemented
- **Image Loading**: Reads images from the dataset folders.
- **Image Preprocessing**:
  - Resizes images to **224x224** pixels for consistency.
  - Converts images from **BGR to RGB** format.
- **Visualization**:
  - Displays tumor and non-tumor images in a grid.
  - Uses `matplotlib` to showcase images with appropriate titles.

## Dependencies
Ensure you have the following libraries installed before running the script:
```bash
pip install opencv-python matplotlib glob2
```

## Dataset Structure
The dataset should be organized in the following structure:
```
DS Project Dataset/
│-- brain_tumor_dataset/
│   │-- yes/  # Contains images of tumors
│   │-- no/   # Contains non-tumor images
```

## How It Works
1. **Reads Images**: The script loads images from `yes/` and `no/` folders.
2. **Processes Images**: Resizes and converts color formats.
3. **Displays Images**: Shows a sample of tumor and non-tumor images in a grid layout.

## Running the Code
Execute the script in a Python environment (e.g., Jupyter Notebook or Colab):
```python
# Run the script in your Python environment
python Data Science-Project.py
```

## Sample Output
The script generates a grid visualization of tumor and non-tumor images, allowing for a quick inspection of the dataset.

---

Feel free to contribute by improving the preprocessing steps or extending the visualization techniques! 🚀

