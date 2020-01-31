# Automatic-Number-Plate-Detection-for-Different-fonts-and-Non-Roman-Scripts
OCR implementation for license plate detection for different fonts and non-roman scripts.

The repository contains 3 tested processed images of cars
car1.JPG its base processed image car1process.JPG and its enhanced resolution image car1processR.JPG
Similarly,
car2.JPG, car2process.JPG and car2processR.JPG
car3.JPG, car3process.JPG and car3processR.JPG

The text extracted from them are stored in,
car1recog.txt, car2recog.txt and car3recog.txt respectively

To test for your own image, imageProcessor.py file is also present
Just fire command:- python extract_text <input_filename> <output_filename>
The script will produce two new processed images with the given output_filename

The script is a Python and Opencv implementation

The process of ectracting text form the processed images is yet not uploaded as we are still working
on traning our model to recognise non-roman fonts (devnagari in specific for prototyping)
Due to insufficient dataset for the traning purpose of non-roman script we are yet not able to achieve the required accuracy
As the dataset of characters for english script is freely available, dataset for non-roman script(devnagari) is not available
However we have collected the dataset manually but is a bit limited

Howerver, we can tell you that we are working on tensorflow with faster-rcnn-v2 model for traning purpose and have achieved good results for english text as in examples given in above txt files.
We still need some brush-up on english to as some text portions are not clear, but we are sure to achieve more accurate results we more training to our model
We also plan to achieve similar results for the non-roman scripts as like english and are delibrately working on the same

For reference to our english character dataset, you can visit https://drive.google.com/open?id=1wrXmFI4IZXzXhqYvlXht4fXK7Saqvf64

We'll soon add up our trained model for both english as well as non-roman script
