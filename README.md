# Project title: Estimatating Solar Radiation in a Particular Location
An end-to-end workflow for extracting the data from sun-photometer (C++ sketches on Arduino IDE) to studying various important quantities derived from the data, which includes aerosol optical depth.

# Tools required
[Arduino IDE](https://docs.arduino.cc/software/ide/)

# Details of the files
data-extractor is an Arduino IDE Sketch which I wrote in C++ language to extract the data from hand-held sun photometer  into an SD card.

Sample-Data contains readings taken by me 4 times-a-day from 10th to 17th December, 2025 from the hand-held sunphotometer. The location was [Physical Research Laboratory, Ahmedabad](https://en.wikipedia.org/wiki/Physical_Research_Laboratory) [Navrangpura] Gujarat.

# Procedure of the Study
1. First you need to give the required dates to "data-extractor", and run this C++ sketch on Arduino IDE. 
2. The console will then show sun photometer readings for those dates. Copy the output and save it in a .txt file.
3. Open the notebook 'SunPhotometer_Langley_Analysis.ipynb' on Google Colab or Jupyter Environment.
4. The saved .txt file needs to be uploaded in the environment of the notebook before running a session.

