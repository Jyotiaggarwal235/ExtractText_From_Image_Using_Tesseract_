 ExtractText_From_Image_Using_Tesseract_Module
 
 
 Installing pytesseract
 
 
 
 
 To install pytesseract, you have to run the following command in your terminal.
 
 
 pip install pytesseract
 
 
 
 
 Downloading and Installing Tesseract
 

 1.Download tesseract from this link.
 
 
 2.And install this as usual as you install other softwares.
 
 
 
 
 Python Program For How To Extract Text From Image
 
 
 newImage.jpeg  is the image in the folder to extract.
 
 
 
 STEPS:-
 
 
 
 1.First of all you have to import Image class from PIL(Python Imaging Library) library. 
 
 
 2.PIL is short form of Pillow and this is the name used for importing the library.
 
 
 3.Image class is required so that we can load our input image from disk in PIL format.
   Then import pytesseract.
   
   
 4.Now you have to include tesseract executable in your path.
   Then you will need to create an image object of PIL library.
   
   
 5.Now you have to pass that image into pytesseract module.
 
 
 6.image_to_string returns the result of a Tesseract OCR run on the image to string.
   Then finally print the text
 
 
 
 
 
