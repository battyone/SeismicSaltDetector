# SeismicSaltDetector

## Pixel-wise dense segmentation of subsurface seismic images for the detection of salt.

Seismic images are obtained by sending artificial seismic waves inside the earth to accurately probe its interiors, for oil and gas exploration purposes. Correct segmentation of the salt (that traps oil and gas) in these images is a major challenge. Analysis of these seismic images usually requires years of experience in the field of geophysics. The natural question therefore is, whether machines can learn the pattern in the seismic images and perform the required segmentation. We take a step toward achieving this by using a convolutional neural network approach. 

## CNN predictions:
The image on the left is an actual seismic image. The second and third columns show the labeled masks and the masks predicted by CNNs, respectively.
<p align="center">
  <img src="https://github.com/des137/SeismicSaltDetector/blob/master/Seismic-Masks-CNNPrediction.png" width="350">
</p>
