# VectorGraphicsTools

## Overview
**VectorGraphicsTools** is a collection of tools for processing and converting raster images into vector graphics. Currently, it includes a script to convert black & white JPG/PNG images into EPS format while preserving contours and nested structures.

## Features
✅ Convert black & white images (JPG/PNG) to EPS format  
✅ Extract and vectorize contours with hierarchical filling  
✅ Preserve nested structures (e.g., outer shapes in black, inner holes in white)  
✅ Apply preprocessing (thresholding, noise removal, morphological operations)  
✅ Preview detected contours before conversion  

## Installation
Ensure you have Python installed, along with the required dependencies:

```sh
pip install opencv-python numpy matplotlib
```

## Usage
Run the script with:

```sh
python jpg2eps.py
```

By default, it processes `backprint.png` and saves the EPS output as `backprint.eps`. To use different files, modify the script accordingly:

```python
input_jpg = "your_image.jpg"
output_eps = "your_output.eps"
```

