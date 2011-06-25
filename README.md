# gmscripts collection ![isgitflowed logo](http://isgitflowed.com/gitflowed_68x13.png)

This is a small collection of graphicsmagick scripts I use for oft-needed batch image operations, such as 

* generating 500px wide blogging-friendly versions of my images or thumbnails
* converting pictures from jpg to png
* batch rotating images

The scripts will process all images inside the current folder, so if you only want to work on a selection, put the images in a temporary folder.

## Usage
Copy the scripts anywhere you like, put the file or folder in your $PATH, make sure it is executable, then navigate to the folder with the images you want to edit and call the respective script from the command line. 

**picconvert** is used in the following way:
	picconvert <original format> <output format> 

e.g.
	picconvert jpg png
