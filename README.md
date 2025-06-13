# Depth Map Enhancement Pipeline

This project implements a Python-based pipeline to enhance depth maps generated from stereo image pairs using the KITTI dataset. It applies CLAHE and TXI algorithms to improve texture and exposure before computing disparity maps.

## Features

- Texture and exposure enhancement with CLAHE and TXI
- Depth map generation from stereo images
- Evaluation of enhanced depth maps using SSIM, edge preservation, noise level, and completeness metrics
- Improved depth quality in low-texture and low-light regions

## Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-image (for metrics)
- KITTI stereo dataset

## How to Run

1. Clone the repository.
2. Install required packages: `pip install -r requirements.txt`
3. Download and prepare the KITTI stereo dataset.
4. Run the enhancement and evaluation scripts.
5. View results and evaluation metrics.

## License

This project is licensed under the MIT License.
