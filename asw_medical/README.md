## Info
Automatic Speech Recognition on AWS for medical domain.

https://user-images.githubusercontent.com/75725664/166889996-97d1a2d9-d3b5-4b3f-a894-08f86bf5859c.mp4

### 1. Installation and run
```
npm install browserify
npm audit fix 
npm install
npm run-script build
npm install —global local-web-server
ws
```
** Works only in Google Chrome. Please run with ngrok if it`s need to use other browsers

### Tech description

Fields and drop lists:
* Access ID - AWS id 
* Secret Key - AWS key
* Language - list of languages (now available only english)
* Speciality - list of available medical domains (Primary Care, Cardiology, Neurology, Oncology, Radiology, Urology)
* Type - dictation types (choose Dictation type to check quality)

### Quality
At the moment we have a basic model for speech recognition in the medical domain for English, the model does not involve deep recognition for complicated English accents. Improvements in the quality of the model will be made in subsequent iterations in the presence of the necessary marked-up data and the collected text corpus. 

