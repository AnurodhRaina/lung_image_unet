# Lung image segmentations using the U-NET model
<UL>
 	<LI>The dataset was sourced from kaggle repository and is available at : 
 https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels/data </LI>
	<LI>It was easily downloaded through the API and the size was around 10GB.</LI>
	<LI>Image parameters:<br>
	&nbsp &nbsp-­‐ Format: PNG<br>
	&nbsp &nbsp-­‐ Image size is 4020 x 4892, or 4892 x 4020.<br>
	&nbsp &nbsp-­‐ The pixel spacing in vertical and horizontal directions is 0.0875 mm.<br></LI>
</UL>

# Data Overview 
<UL><LI>Some of the
	sample images 
	from the dataset. </LI>

<LI>Data is well 
	masked.
</LI>
</UL>
<br>
<img src="[https://user-images.githubusercontent.com/link-to-your-image.png](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/8a0337ab-b280-4649-baf2-f514adba7466)" height 300 width="200" />


![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/8a0337ab-b280-4649-baf2-f514adba7466)

# Data Processing
<UL>
	<LI>Conversion to grayscale</LI>
	<LI>Resizing to 256x256</LI>
	<LI>Convert and store to array</LI>
	<LI>Augment and create more</LI>
</UL>

![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/defa7f37-b917-43fe-9e7c-7b71adfebb5a)

<hr>
<UL>
	<LI>Before augmentations 500 valid images and masks were present</LI>
	<LI>Augmentations helped double the size to a 1000 images and mask.</LI>
	<LI>Albumentations library was used for augmentations.</LI>

</UL>


# U-NET Architecture
* Classic U-net with custom layers and filters.
* Less layers for less complex dataset

![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/69093154-e1aa-4cdb-8684-ed9275e1fccb)



