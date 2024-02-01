# Crop-image
## Description-
This Python script utilizes the OpenCV library for basic image processing. It loads an image ('download.png'), displays the original and cropped versions, saves the cropped image as 'Cropped Image.jpg', and waits for user input to close the display windows. The main operation involves cropping a region of interest from the original image.
## Explanation-
  -Loading Image: Reads an image file ('download.png') using OpenCV's imread function and prints its shape.

  -Displaying Original Image: Displays the original image using imshow.

  -Cropping Image: Defines a region of interest (ROI) in the original image (from row 80 to 280 and column 150 to 330) and extracts the cropped image.

   -Displaying Cropped Image: Displays the cropped image using imshow.

   -Saving Cropped Image: Writes the cropped image to a new file ('Cropped Image.jpg') using imwrite.

   -Waiting for User Input: Waits for a key press to close the OpenCV windows.

   -Closing Windows: Closes all OpenCV windows after user input.
