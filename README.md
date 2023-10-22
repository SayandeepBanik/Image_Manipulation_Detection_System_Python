# Image Manipulation (Forgery) Detection System
In today’s technical world, the digital image is a vital part of many application domains. The meaning of image forgery is the manipulation of digital images to hide important information or output false information. Due to the introduction of modern image processing tools, digital image forgery is at its peak. Copy-move forgery is one of the most commonly used techniques to perform image forgery. The aim of the proposed system is to detect and highlight the malpractices performed on modern-day digital images.

# Image Forgery Detection Tool
The forgery detection tool contained in this repository currently features forensic methods to detect the following:

- Double JPEG compression
- Copy-move forgeries
- Metadata Analysis
- CFA artifacts
- Noise variance inconsitencies
- Error Level Analysis
- Image Extraction
- String Extraction
- For More Detail - [Research Paper](https://journals.grdpublications.com/index.php/ijprse/article/view/537/507)

## To Run:
<!-- Place any(JPEG) images that you wish to analyze into the **image** folder Present in the Project directory. -->

Navigate to the **Project** directory:
```
$ cd Image_Manipulation_Detection_System_Python
```

Next, run the **detect.py** script, providing the image you wish to evaluate:
```
$ python GUI.py
```

Once finished, details on the image will be reported in the terminal. Supplemental images generated during copy-move forgery detection can be found in the output directory.

##  IMAGES
![Screenshot 2023-10-22 093741](https://github.com/SayandeepBanik/Image_Manipulation_Detection_System_Python/assets/139032216/2b15383b-245d-4191-b9b8-fea63c172e15)


![Screenshot 2023-10-22 093752](https://github.com/SayandeepBanik/Image_Manipulation_Detection_System_Python/assets/139032216/09b7d215-7eb0-48bd-88ab-3b3938301740)




