# pixel_art
this is a pixel art generator in python

this is a very simple tool to build pixel art images based on raw images  
it uses open cv library to perform the hereunder steps:  
1. load image  
2. remove background  
3. resize image to the targeted reduced %  
4. simplify colours to the targeted bins  

parameters may need to be tuned to achieve proper removal of the background  
it works best with images around 250 x 250 as you can find on internet  

here is a good example of what it does step by step:  

![alt text](https://github.com/JeanMILPIED/pixel_art/blob/master/pixel_generator.JPG)

