Methods:
We tried Stenography, LSB and MSB analysis, tried tools like exiftool etc. They did not work. We also checked for the meta data of the image. At first we thought its related to the history of the image, we found that the image is from "Blue Ocean". But on searching online, we realised that its related to image forensics, so we would have to look into the metadata, strings etc.

Final Method:
Using foresnsically on google, the strings of the image was found. On some research, some of the strings looked like ASCII.
By line by line conversion(ASCII) in base 64 encode, the flag was found.
