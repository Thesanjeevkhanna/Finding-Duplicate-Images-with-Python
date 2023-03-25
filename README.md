# Finding-Duplicate-Images-with-Python
A Python code for Identifying Duplicate Images in a Folder.

This code only checks for JPEG,JPG files and does not support other image file formats such as PNG or GIF and it only checks for duplicate 
images based on their mean pixel values.

This code may take more time for large collections of images. This is because the code reads in all the images in the folder and calculates the mean pixel values for each image,
which can be a computationally expensive operation, especially if the images are large.

How to run:
just run newimgdup.py in visual code or any other python compiler,before that set correct location of file path in folder_path and then run the code.... 
