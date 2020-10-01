# License Plate Detection Using YOLO

A license plate detector that extracts plate information in real time. 

### Tech

The detector is built using the darkflow framework for object detection and classification. The object detection and classification is done using the YOLO algorithm. Once the license plate has been detected, the relavent information is then extracted from the image using tesseract OCR.

* [darkflow] - Real-time object detection and classification 
* [tesseract] - OCR engine for extraction of characters from detected license plates

### Dependencies
Python 3, tensorflow 1.0, numpy, opencv 3, darkflow, tesseract

### Running the detector
* Download the weights and getPlate.py python script
* Specify the location of the weights under options in the python script
* Run the python script as follows

```sh
python3 getPlate.py
```

[darkflow]: <https://github.com/thtrieu/darkflow>
[tesseract]: <https://github.com/tesseract-ocr/tesseract>
