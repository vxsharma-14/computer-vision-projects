# Computer Vision Projects

computervision #panopticsegmentation #instancesegmentation

## Projects

1. **Panoptic Segmentation**
   - **Notebook**: `panoptic_segmentation.ipynb` ([Notebook link](panoptic_segmentation.ipynb)
   - **Description**: Identifies and extracts specific objects from images using panoptic segmentation, then composites those objects onto a transparent background.
   - **Platform** - detectron2 by Facebook Research
   - **Example**:
     - Original Image: `/images/originals/example1.jpg` (Image Source: [COCO Dataset](https://farm8.staticflickr.com/7019/6743930825_20b705cc5c_z.jpg))
       ![Original](https://github.com/vxsharma-14/computer-vision-projects/blob/main/images/originals/example1.jpg))
     - Inferred Image: `/images/output/example_panoptic.jpg`
       ![Inferred Image](https://github.com/vxsharma-14/computer-vision-projects/blob/main/images/outputs/example_panoptic.jpg)
     - Masked Image: `/images/outputs/example_masked.jpg`
       ![Masked Image with Transparent bg](https://github.com/vxsharma-14/computer-vision-projects/blob/main/images/outputs/example_masked.jpg)
  
## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cv-object-segmentation.git
   cd cv-object-segmentation

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage

1. Place your input images in the `root/images/originals/` directory.
2. Run the relevant Jupyter notebook.
3. Adjust the `class_names` variable to specify the objects you want to extract.
4. View the results in the `root/images/masked/` directory.

## License

This project is licensed under the MIT License - see the [LICENSE](license.md) file for details.
