# BusinessCardReader
2019 USTH ICT final thesis project: Business Card Reader

To use (recommended in Linux environment or Google Colab):

* Dependencies:
```
!sudo apt install tesseract-ocr
!pip install pytesseract
!pip install fuzzywuzzy
!pip install python-Levenshtein
!pip install find-job-titles
!pip3 install -U nltk
!sudo apt-get install openjdk-8-jre
```
* Run the `perspective_trans` function in PerspecTrans.ipynb to get a top-down look from an image
* Run the `detect_text_2` function in OCRPreprocessing.ipynb to extract the text and its x,y,w,h
* Before running the 'detect_info_v2' function to get a final classification result, one must run a StanfordCoreNLP local server and export it to port 9011 (or just change the port in the main code)


