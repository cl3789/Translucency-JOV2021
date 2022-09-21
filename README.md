# Crystal or Jelly? Effect of Color on the Perception of Translucent Materials with Photographs of Real-world Objects

Chenxi Liao, [Masataka Sawayama](https://www.mswym.com/), [Bei Xiao](https://sites.google.com/site/beixiao/?pli=1&authuser=2)

Abstract: Translucent materials are ubiquitous in nature (e.g. teeth, food, and wax), but our understanding of translucency perception is limited. Previous work in translucency perception has mainly used monochromatic rendered images as stimuli, which are restricted by their diversity and realism. Here, we measure translucency perception with photographs of real-world objects. Specifically, we use three behavior tasks: binary classification of “translucent” versus “opaque,” semantic attribute rating of perceptual qualities (see-throughness, glossiness, softness, glow, and density), and material categorization. Two different groups of observers finish the three tasks with color or grayscale images. We find that observers’ agreements depend on the physical material properties of the objects such that translucent materials generate more interobserver disagreements. Further, there are more disagreements among observers in the grayscale condition in comparison to that in the color condition. We also discover that converting images to grayscale substantially affects the distributions of attribute ratings for some images. Furthermore, ratings of see-throughness, glossiness, and glow could predict individual observers’ binary classification of images in both grayscale and color conditions. Last, converting images to grayscale alters the perceived material categories for some images such that observers tend to misjudge images of food as non-food and vice versa. Our result demonstrates that color is informative about material property estimation and recognition. Meanwhile, our analysis shows that mid-level semantic estimation of material attributes might be closely related to high-level material recognition. We also discuss individual differences in our results and highlight the importance of such consideration in material perception.


Paper is available on [JOV](https://jov.arvojournals.org/article.aspx?articleid=2778489) 

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

## Note
- Authors own the copyright for the images in **own_copyright_images_stimuli** and **replaced_images_with_copyright** folders. The images are under Creative Commons Attribution 4.0 International License.
- For the images in **300_ImgColor** folder (those are not included in **own_copyright_images_stimuli**), authors do not own the copyright of them. 




