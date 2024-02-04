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

![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/8a0337ab-b280-4649-baf2-f514adba7466)

# Data Processing
<UL>
	<LI>Conversion to grayscale</LI>
	<LI>Resizing to 256x256</LI>
	<LI>Convert and store to array</LI>
	<LI>Augment and create more</LI>
</UL>

![image](https://github.com/AnurodhRaina/lung_image_unet/assets/51761306/3e3c32c6-2f45-4452-9746-d0b8efb0c7b4)


