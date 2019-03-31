# image_recognition_walkthrough
A walkthrough for creating a basic image classifier

This repo contains a tutorial for creating and training a convolutional neural network (CNN) to classify images as containing either an refridgerator and a washing machine.

1. Scraping Google Image Search for Image Data
2. Creating and training a CNN to diffentiate between apples and bananas.

## 1. Scraping Google Image Search for Image Data

This folder contains a script for reading images from Google Image search. Credit for the code and instructions for using the file are located at:

https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/

### Javascript:

The .js file contains code that can be input into the console of a Google Image search to download image links automatically.

	NOTE: Use Chrome, not Firefox.

### Python:

The .py file contains a script that when run will download the images from the links provided. To run the script, cd into the folder and run:

    python download_images.py --urls urls.txt --output images/target

	NOTE: 	"urls.txt" should be replaced with the name of the file containing the links.
		      "images/target" should be replaced with the path to the location you'd like to save the images to.
          The script should be run twice for refridgerators and washing machines
    
