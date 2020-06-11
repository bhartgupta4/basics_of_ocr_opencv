# basics_of_ocr_opencv

There is a combination of Pillow, OpenCV, and Pytesseract
Take a ZIP file of images and process them, using a library built into python. A ZIP file takes several different files and compresses them, thus saving space, into one single file. The files in the ZIP file we provide are newspaper images,to write python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza". use OpenCV to detect faces,use tesseract to do optical character recognition,  use PIL to composite images together into contact sheets.

Each page of the newspapers is saved as a single PNG image in a file called images.zip. These newspapers are in english, and contain a variety of stories, advertisements and images.
