
#Tessdata 


### What have we done different? 

Though [Tesseract](https://github.com/tesseract-ocr/tesseract) supports Indic scripts, the approach tesseract  takes to train models for languages like Tamil, Malayalam, Oriya, Gujarati, Kannada and Telugu is same as those for English, French or Spanish. 

This fails often for Indic Scripts because in languages mentioned above, some characters which are dependent on consonants occur before the consonants and these characters turn out wrong while tesseract scans the image left to right. 

We have trained tesseract to interpret these characters as individual glyphs so that they can be post-processed later. 


 


### Trained Models for Indian Languages.

Tesseract Models (Traineddata) are being made available for all the Indic Scripts here including Santali and Meetei Meyek. We have used [Noto Fonts ](https://www.google.com/get/noto/) to train all the scripts. These models are to be expected to have more accuracy than the ones provided through tesseract site 

###The languages currently covered are 

* Bengali (ben)
* Gujarati (guj)
* Hindi (hin)
* Kannada (kan)
* Malayalam (mal)
* Meetei Meyak (mni)
* Oriya (ori)
* Punjabi (pan)
* Santali (sat)
* Tamil (tam)
* Telugu (tel)


### Installation 

Please install tesseract for your OS system <https://github.com/tesseract-ocr/tesseract/wiki> and then copy these models (traineddata files) to tessdata directory. 

### Future plans 

In future we have plans to release Sinhalese and Thai too 

### Authors and Contributors

@rkvsraman

### Support or Contact

If you  can help or need help in training a new font or a new language which is identical to Indic Scripts (Khmer, Laos , Thai etc)  please feel free to join the team and contribute 
-[Team Indic OCR](https://github.com/indic-ocr)  
