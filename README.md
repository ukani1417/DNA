# DBGPS Application Guide 

This text file is a guide to the Application

## Purpose :

The purpose of this application is to demonstrate the encoding and decoding process.
We have used Outer Fountain Encoding and Decoding along with DBGPS algortihm.
The application is able to do the following:

    - Encode a zip file of an image to DNA strands
    - Decode the DNA strands to recover the original zip file with images.
    - A status bar at the bottom shows the status of the operation being performed.

## Constraints:

    - The input file for encoding must be a zip file of images only
    - The images should be of extension .jpg and must be of size greater than 500KB
    
## Usage Steps:
   Run the Run_Application.py file or click the Setup.exe file to start the application
    
   ### Encoding :
        - Click on encode button
        - Choose the zip file to be encoded
        - Encoding process will begin and once completed the encoded file location will be shown in the status bar 
        - The file size will be shown on the label above the encode button

   ### Decoding : 
        - Enter the original file size in the textbox that was shown after encoding was completed
        - Click on decode button
        - Choose the encoded file to be recovered
        - Decoding process will begin and once completed the decoded file location will be shown in the status bar        
