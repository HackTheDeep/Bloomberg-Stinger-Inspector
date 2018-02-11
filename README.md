# hack-the-deep
Hack the Deep @ AMNH 2018/2/10

# Team Name: Bloomberg Stinger Inspector (Team U)

## Team Members  
Gautam Shine  
Eric Cheng  
Tuba Opel  

## Our Challenge
[Stinger Inspector](https://github.com/amnh/HackTheDeep/wiki/Stinger-Inspector): Use Computer Vision and Machine Learning to Reclassify Cnidarians. {Estefania Rodriguez and Luciana Gusmão}

## Our Solution

### MeasuredData Script: Parses Live Measured Data Files
1) Identifies the capsule within the image    
2) Calculates the length and width of the capsule  
3) Orient the capsule so the length is horizontal to the x-axis

### Edge Detection Script: Image Enhancement and Noise Reduction
1) Converts images to grayscale to format them for image enhancement
2) Applies thresholding filters onto images to reduce noise
2) Uses multiple edge detection algorithms on images to detect edges of nematocysts
