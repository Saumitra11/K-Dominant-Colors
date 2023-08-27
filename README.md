# K-Dominant Colors

K-Dominant Colors is a Python project that extracts the most dominant 'K' colours from images using the K-Means Clustering algorithm.

## Objective

The primary objective of this project is image segmentation. Image segmentation involves dividing an image into distinct regions that share similar visual characteristics, often corresponding to different parts of objects within the image.

## Key Features

- Utilizes the K-Means Clustering algorithm to extract dominant colours from images.
- Provides a customizable parameter 'K' to control the number of dominant colours to be extracted.
- Supports applications like Color Palette Generation, Color Compression, and Image Analysis and Visualization.

## How it Works

1. The K-Means Clustering algorithm groups pixel colours in an image into 'K' clusters.
2. The centre of each cluster represents a dominant colour.
3. The 'K' dominant colours are then extracted from the image, which can be used for various purposes.

## Installation

1. Clone the repository: `git clone https://github.com/Saumitra11/K-Dominant-Colors.git`
2. Navigate to the project directory: `cd k-dominant-colors`

## Usage

1. Run the script: `python k_dominant_colors.py path/to/your/image.jpg k_value`
   - Replace `path/to/your/image.jpg` with the path to the image you want to process.
   - Replace `k_value` with the desired number of dominant colours (integer value of K).

## Applications

- **Color Palette Generation:** Create visually pleasing colour palettes for various design projects.
- **Color Compression:** Reduce the number of colours in an image to optimize storage and transmission.
- **Image Analysis and Visualization:** Extract meaningful information from images for data analysis and visualization.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## Contact

For questions or feedback, you can reach us at [saumitrapathak11@gmail.com](mailto:saumitrapathak11@gmail.com).

---

*Disclaimer: This project is for educational purposes and does not guarantee perfect colour segmentation.*
