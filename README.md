
#  MEDOCKER

AI powered document digitizer (Hand written recognition)
![Medocker_Banner](https://user-images.githubusercontent.com/9859576/215635136-4625a7bf-1f9e-480c-893b-1528302cfe01.jpg)


## Authors

- [@alxv](https://www.github.com/alxv)

Lauren Walker, Alexandar Vincent Paulraj
## Features

- Automatic identification of region of interest(ROI)
- Extract ROI
- Digitise handwritten text
- Store results in a CSV file


## Documentation

Handwritten documents must be digitised to improve storage, access, search, and analysis. Prior to the deep learning revolution, there was no clear path to achieve such a goal in a scalable manner. Because of the variability of handwriting, automatic text detection and segmentation can be error-prone and frequently require custom preprocessing.

Recent Deep Learning advances, such as the introduction of transformer architectures, have accelerated our progress in handwritten text recognition. Recognizing handwritten text is referred to as Intelligent Character Recognition (ICR) because the algorithms required to solve ICR require significantly more intelligence than solving generic OCR.

## Deployment

### Run in Colab
1. Download and open Medocker.ipynb in google colab.
2. Set GPU session.
3. Downolad sample images and corresponding template from this repository
4. Follow the instructions metioned in Medocker.ipynb file

### Local implementation (GPU required)
1. Clone this repository
2. Run the Medcoker.ipynb file


## How to adapt this project for your work
### You need make Four major modification
1. Your template/unfilled form (image)
2. Get cordinates for region of of interests in your template
 ### How to get XY cordinates for ROI
![Gif_medoc](https://user-images.githubusercontent.com/9859576/215634929-a499507a-a46d-475b-8a34-92d2f330c8cc.gif)

3. Update the XY values in the (Setting region of interests) section of ipynb file.
4. dataoutput.csv should contain names of ROI (header only)

## Hardware
[Manual_git.pdf](https://github.com/alxv/medocker/files/10541584/Manual_git.pdf)

## Acknowledgements
Microsoft -trocr-large-handwritten & Huggingface


