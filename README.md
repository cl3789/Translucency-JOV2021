# Crystal or Jelly? Effect of Color on the Perception of Translucent Materials with Photographs of Real-world Objects

Chenxi Liao, [Masataka Sawayama](https://www.mswym.com/), [Bei Xiao](https://sites.google.com/site/beixiao/?pli=1&authuser=2)

## Stimuli

**300_ImgColor**
The stimuli used in the color condition in the main paper.

**300_ImgGray_Lightness**
The stimuli used in the grayscale condition in the main paper. The RGB images are converted to CIELab space, and we extracted, duplicated, and then concatenated the lightness channel.

**Gray_contrast preserved**
The stimuli used in the grayscale condition in the supplementary material. The RGB images are converted to the grayscale by using a Contrast Preserved Decolorization method in OpenCV (Lu et al. (2012)).

**Label_flipped_image**
Different types of classification label flips when the images are converted to grayscale (extracted Lightness channel). For example, “Opaque -> Translucent” means the image flips its label from opaque to translucent when it is converted to grayscale.

## Experiment data
**Results Catalogue.csv**
Contains the description of data of results in "exp data" folder

## Analysis
**Code Catalogue.csv**
Contains the description of codes used for the analysis in "Analysis" folder




