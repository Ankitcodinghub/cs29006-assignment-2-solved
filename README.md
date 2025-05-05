# cs29006-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS29006 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs29006-assignment-2-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100666&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS29006 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# Software Lab

## Python Datascience Assignment

In this assignment we will deal with **Object detection**. Object detection is a very well studied task of Deep Learning, having tremendous variety of applications. You have to create a python package for transforming images and analysing their effect on the predictions of an object detector. We are providing you with a pretrained object detector, all you need to do is to call the detector on the image and get the outputs.

A python package means that one can install the package in the python environment and can import the modules in any python script, irrespective of the location of the script. Creating a python package is fairly easy, just follow the steps [here](https://packaging.python.org/tutorials/packaging-projects/).

The details of each of the files/folders are as follows:

1. `main.py`: This is the main file which is to be called to execute the program. The main file calls the corresponding functions as needed while execution. The main file should call the appropriate function to prepare the dataset, then transform the images read, obtain the bounding boxes of the objects present in the image by calling the detector model, and then plot the obtained images by calling the appropriate functions from the package described below.

2. `./my_package/model.py`: This file contains the object-detection model definition. Consider it as a black-box model which takes an image (as numpy array) as input and provides the bounding box outputs and the corresponding class labels as for the input image.

&amp;nbsp;

&lt;p align=”center”&gt;

&lt;img src=’./sample_imgs/bbox.png’ width=400&gt;

&lt;/p&gt;

&lt;p align=”center”&gt;

&lt;b&gt;Fig. 1&lt;/b&gt;. Sample Output of an Object Detector. &lt;/p&gt;

&amp;nbsp;

3. `./my_package/data/dataset.py`: This file contains the class “`Dataset“` that reads the provided dataset from the annotation file and provides the numpy version of the images which are to be transformed and forwarded through the model. The annotation format is provided in `data/README.md`

4. `./my_package/data/transforms`: This folder contains 5 files. Each of these files is responsible for performing the corresponding transformation, as follows:

a) `crop.py`: This file takes an image (as numpy array) as input and crops it based on the provided arguments. Declare a class `CropImage()` for performing the operation.

&amp;nbsp;

&lt;p align=”center”&gt;

&lt;img src=’./sample_imgs/crop.png’ width=400&gt;

&lt;/p&gt;

&lt;p align=”center”&gt;

&lt;b&gt;Fig. (a)&lt;/b&gt;. Crop Operation. &lt;/p&gt;

&amp;nbsp;

b) `flip.py`: This file takes an image (as numpy array) as input and flips it based on the provided arguments. Declare a class `FlipImage()` for performing the operation.

&amp;nbsp;

&lt;p align=”center”&gt;

&lt;img src=’./sample_imgs/flip.png’ width=400&gt;

&lt;/p&gt;

&lt;p align=”center”&gt;

&lt;b&gt;Fig. (b)&lt;/b&gt;. Flip Operation. &lt;/p&gt;

&amp;nbsp;

c) `rotate.py`: This file takes an image (as numpy array) as input and rotates it based on the provided arguments. Declare a class `RotateImage()` for performing the operation.

&amp;nbsp;

&lt;p align=”center”&gt;

&lt;img src=’./sample_imgs/rotate.png’ width=400&gt;

&lt;/p&gt;

&lt;p align=”center”&gt;

&lt;b&gt;Fig. (c)&lt;/b&gt;. Rotate Operation. &lt;/p&gt;

&amp;nbsp;

d) `rescale.py`: This file takes an image (as numpy array) as input and rescales it based on the provided arguments. Declare a class `RotateImage()` for performing the operation.

&amp;nbsp;

&lt;p align=”center”&gt;

&lt;img src=’./sample_imgs/rescale.png’ width=400&gt;

&lt;/p&gt;

&lt;p align=”center”&gt;

&lt;b&gt;Fig. (d)&lt;/b&gt;. Rescale Operation. &lt;/p&gt;

&amp;nbsp;

e) `blur.py`: This file takes an image (as numpy array) as input and applies a gaussian blur to it based on the provided arguments. Declare a class `GaussBlurImage()` for performing the operation.

&amp;nbsp;

&lt;p align=”center”&gt;

&lt;img src=’./sample_imgs/blur.png’ width=400&gt;

&lt;/p&gt;

&lt;p align=”center”&gt;

&lt;b&gt;Fig. (e)&lt;/b&gt;. Blur Operation. &lt;/p&gt;

&amp;nbsp;

5. `./my_package/analysis/visualize.py`: This file defines a function that draws the image with the predicted bounding boxes (with the corresponding labels) on the image and saves them in the specified output folder.

6. `setup.py`: Use this file for constructing the package `my_package`.

## Coding Task [30 marks]

Note: For handling images, e.g. reading images, etc. we would recommend using PIL instead of OpenCV as OpenCV uses `BGR` format instead of `RGB`.

1. Write the various transformations in `./my_package/data/transforms`. There are five files, as already mentioned. Although these functions are easily implementable using numpy only, you may use any image processing libraries like PIL, skimage or opencv. [2×5=10 marks]

2. Complete the `Dataset` class in `./my_package/data/dataset.py`. This class will accept the path to the annotation file and the list of transformation classes. Ideally you should be directly using transformation classes but you may also use strings to identify the transformations. [5 marks]

3. Write a function `plot_boxes()` in `./my_package/analysis/visualize.py` that will draw the image with the predicted bounding boxes (with the corresponding labels) on the images and save them in the output folder specified in the argument. Please note that you need to plot only the 5 most confident bounding boxes predicted by the object detector. If the detector predicts less than 5 boxes, then plot all of them. [5 marks]

4. Create a python package “` my_package“`. For this you need to write “` setup.py“`. It must be noted that files called “`___init__.py“` need to be added in the hierarchy. We leave it to you to search where they should be added. Note that the user will generally not know the exact files where the classes are written. That means, he does not know that their exist a file “`crop.py“` where the class “`CropImage()“` is defined. Rather he simply knows that this class is defined in “`transforms“`. So, a good coding practice is to allow an import statement “`from my_package.data.transforms import CropImage“`. [5 marks]

5. Write “`main.py“` where you will test the different transformations you have written on the object detector. The outputs for each of the experiments should be organized properly in the outputs folder. [5 marks]

## Analysis Task [10 marks]

1. Obtain and save the predicted bounding boxes for all the images provided in the `data/imgs` folder. [3 marks]

2. Consider the image with name same as the last digit of your roll number, i.e. if your roll number is 19CS####7 then consider the image `7.jpg` then plot the following using `subplots` in matplotlib and save them: [1×7=7 marks]

a) The original image along with the predicted bounding boxes.

b) Horizontally flipped original image along with the predicted bounding boxes.

c) Blurred image (with some degree of blurring) along with the predicted bounding boxes.

d) Twice Rescaled image (2X scaled) along with the predicted bounding boxes.

e) Half Rescaled image (0.5X scaled) along with the predicted bounding boxes.

f) 90 degree right rotated image along with the predicted bounding boxes.

g) 45 degree left rotated image along with the predicted bounding boxes.

**Please read the class definitions very carefully. In this assignment you do not need to code a lot, but you need to understand how to integrate several custom modules together in a clean way. More details on the arguments and the return types are provided in the corresponding files.**
