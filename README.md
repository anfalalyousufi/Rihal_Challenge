# Rihal_Challenge
## Intro:
The solution needs to do the following steps: 
1.Input/Upload this PDF document 
2.Use page 2 for the data. 
3.OCR the page 
4.Extract the following as outputs: 
  a) Find all dates. Standardize the finding to this format MM/DD/YY 
  b) All serial numbers 
    i. Should be separated as 1 st value 2 nd value 3 rd value 4 ht value 
  c) All cities 
  d) All ages 
  e) All cat names
  
  ## Reference:
  https://www.geeksforgeeks.org/python-reading-contents-of-pdf-using-ocr-optical-character-recognition/
  https://pdf.wondershare.com/how-to/extract-images-from-pdf-python.html
  https://www.geeksforgeeks.org/reading-images-in-python/
  
  ## Solution:
  Commands to install packages
    pip install pathlib
    pip install pdf2image
    pip install pillow
    pip install pytesseract
    pip install tesseract-ocr tesseract-ocr
    conda install -c mcs07 tesseract
    
  Step 1: PDF -> jpg
  Step 2: Use pytesseract to convert image to text
  Step 3: Find similarities and display the result
  
  ## Running the code:
  Step 1: Python file and pdf file should be in the same file
  
  ## Output
