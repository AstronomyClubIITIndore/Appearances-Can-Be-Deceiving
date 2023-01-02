# Appearances-Can-Be-Deceiving
With the large amount of data from our favorite telescopes being accumulated everyday, there’s not many people to ponder over it. The need for software tools which can perform specific functions on the data, is ever increasing. These softwares are utilized to their best when they are open source i.e, web tools.



## Problem Statement:
Introduction:
Understanding the characteristics and life cycle of stars has been something that astronomers have been doing for a long time, and it still continues. One of the characteristics of stars is their surface temperature, which is key to understanding the type of star we are looking at.
Handy tools which can figure out certain properties of cosmic bodies, help people like theoretical astrophysics to model the observations are rare. The goal of this problem statement is to build one of such tools.

Given a minimum of 2 FITS files of the same star/cluster at different wavelengths/bands of observation, you are required to estimate the apparent surface temperature of significant stars in the image.

### Task: 
1. Develop a web portal which can accept multiple FITS files of the same patch of sky at different wavelengths.
2. The files may be then processed (on client or at backend) and the image should be displayed on the portal. The apparent temperature of the significant stars in the image should be shown on the portal on being hovered, on the star. Include a range of hovering for individual stars.
3. The test files will be in Blue and Red bands of the optical range.

### Output: 
It is expected that the application is able to take FITS file inputs and render the image; when hovered upon stars in the rendered image, a surface temperature range of the star should be displayed. This application should be a web tool.
Submission: Submissions will be through google forms, which take the github link and a brief writeup of the solution. Writeup is not necessary for a solution to be accepted, but it would carry marks. The solution would be accepted even if not complete.

### Marking Scheme: 
70 (solution)+ 10(writeup) + 20(pitching)

### Other Details:
Design and Tech stacks can be of your choice. 
Solution should also contain necessary readme files to run the application on a local machine.
There are various methods to find the temperature of a star, select the appropriate suitable for the given data, even though it’s not much more accurate than the others.

### Note:
The necessary wavelengths will be provided in the FITS file. Though the images from DSS are flux calibrated, it is advised to scale down flux values in the images suitably for processing. The necessary pixel data will be present in the FITS file.

### Test Data Files:
You have been provided with 2 FITS files of the same image in blue and red band from the DSS archive.

Note: These extended tasks carry lesser weightage than the original task, however they are an extraordinary addition to the solution. (carry bonus points)
Extended Task 1: Allow input of more than 2 files, i.e., IR bands to be included, which can help for even accurate results.
Extended Task 2: Using the RA and Dec v/s pixel parameters given in the FITS file you may also display the RA and Dec coordinates of the file.



