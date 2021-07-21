# Scraping-Google-Images
Python and Js code for scraping google images

1. Search the required images on google
2. Scroll till the point you want images to be scraped
3. Inspect element, open console and enter the javascript code included in the text file of this repo [here](https://github.com/dhananjay1710/Scraping-Google-Images/blob/main/RunCodeInConsoleOnGoogleImages.txt)
4. It will automatically download a file named urls.txt which will contain the image file.
5. Place the file in a folder along with the python file included in this repo [here](https://github.com/dhananjay1710/Scraping-Google-Images/blob/main/google_images_extraction.py)
6. Open CMD in the folder and type the following lines:

```
 python google_images_extraction.py --urls urls.txt --output images/santa
```

the arguments here are:
  urls: The file downloaded  by our js code
  output: the location where we want our images to be stored. 
  *** Please Note, the folder must be created before hand ***
  
  
  For any issues with following the process, refer to this [link](https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/)
