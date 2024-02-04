# Lung image segmentations using the U-NET model
## Objective : Realizing how adjustment to filters and layers affect the spatial information in model training and output.

<UL>
 	<LI>The dataset was sourced from kaggle repository and is available at : 
 https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels/data </LI>
	<LI>It was easily downloaded through the API and the size was around 10GB.</LI>
	<LI>Image parameters:<br>
	&nbsp &nbsp-­‐ Format: PNG<br>
	&nbsp &nbsp-­‐ Image size is 4020 x 4892, or 4892 x 4020.<br>
	&nbsp &nbsp-­‐ The pixel spacing in vertical and horizontal directions is 0.0875 mm.<br></LI>
</UL>

# DATA OVERVIEW 
<UL><LI>Some of the
	sample images 
	from the dataset. </LI>

<LI>Data is well 
	masked.
</LI>
</UL>
<br>
<img src="https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/8a0337ab-b280-4649-baf2-f514adba7466" height= "800" width="600" />


# DATA PROCESSING
<UL>
	<LI>Conversion to grayscale</LI>
	<LI>Resizing to 256x256</LI>
	<LI>Convert and store to array</LI>
	<LI>Augment and create more</LI>
</UL>
<img src="https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/defa7f37-b917-43fe-9e7c-7b71adfebb5a" height= "800" width="600" />

<hr>
Before augmentations 500 valid images and masks were present 
Augmentations helped double the size to a 1000 images and mask. 
Albumentations library was used for augmentations.



# U-NET ARCHITECTURE
* Classic U-net with custom layers and filters.
* Less layers for less complex dataset
<img src="https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/69093154-e1aa-4cdb-8684-ed9275e1fccb" height= "800" width="1400" />




# RESULT & OUTPUTS
<img src= "https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/894831f7-6b30-47f0-be9d-2dc063851d50" width = "800" height = "600"/>

## Example Outputs:
![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/51cd06d9-5189-4987-a44d-7cdf62440887)
![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/7a340509-fdd4-4430-a95c-6400f10c9488)
![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/a4f3a5a5-4f0c-4e3c-9311-5e28782e55b6)




