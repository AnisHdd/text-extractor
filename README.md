# text-extraction-
The aim of this Notebook is to extract a text from file (include the PDF format)

# Ojbectifs :
* The objective of this notebook is to extract words from a document (png, jpeg, jpg,...) and store them in a list and create an associated txt file. Then search for a certain word in this list. 
* The pdf documents must first be converted 
* To specify the language you just have to change the lan parameter in the extract_words function. Example 'ara' for Arabic, 'fra' for French or 'ara + fra' for both.
* The list of supported languages is obtained by the command print(pytesseract.get_languages(config='')) 
# Installation of modules:
* pip3 install pytesseract
* pip3 install opencv-python
* You also have to install tesseract with brew install tesseract-lang . See https://stackoverflow.com/questions/52891563/how-to-install-language-in-tesseract-ocr for the installation of tesseract on other OS 
* tesseract documentation is available here https://pypi.org/project/pytesseract/
* brew install poppler 
* conda install pdf2image
