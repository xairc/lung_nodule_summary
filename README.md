# lung_nodule_summary
summary lung nodule with 9 attribute

# Prerequisites
python 3.5.2      
pytorch 0.2.0

# lidc 9 attribute
 - malignancy (range: 1~5)
 - sphericity (range: 1~5)
 - margin (range: 1~5)
 - spiculation (range: 1~5)
 - texture (range: 1~5)
 - calcification (range: 1~6)
 - internal structure (range: 1~4)
 - lobulation (range: 1~5)
 - subtlety (range: 1~5)

# Data Download
 - lung nodule data from lidc
 - https://luna16.grand-challenge.org/download/
   - download data and candidates_V2.csv
 - https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI
   - download Radiologist Annotations/Segmentations (XML)

# Execution Flow
 - Download Data
 - set path with config_training.py
 - python prepare.py 
    - for make preprocessing data
 - python rule.py
    - see result of lidc nodule summary
