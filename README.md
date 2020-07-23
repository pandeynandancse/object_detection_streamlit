# object_detection_streamlit
A web app that shows the use of pretrained  caffemodel 


## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Directory Tree](#directory-tree)
  * [Installation](#installation)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Contribution](#contribution)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [Credits](#credits)


## Demo

![](https://i.imgur.com/JNfwo9B.jpg)



## Overview
A web Application developed via streamlit for neural style transfer using Tensorflow . It provides flexibility to experiment with various ways. You can set various parameters of your choice and can see different different results.


## Directory Tree 
```

├── images
|    ├── content_images
|    ├── style_images
|    ├── logo_image
├── outputs
|    ├── images
|    ├── videos
├── README.md
├── activation.bat
├── final.py
├── requirements.txt

```
In above directory structure outputs folder is created only when images and videos is required by user. Facility for choosing this option is given at top of side-bar of application.

## Installation
1. Windows user can double click on activation.bat file to install required package
2. Linux User type following command in commnand line
a) First create a virtual environment 
```bash
python3.7 -m virtualenv venv
```
b) Move to venv directory and activate environment
```bash
cd venv
. bin/activate
```
c) Clone this project 
```bash
git clone https://github.com/pandeynandancse/object_detection_streamlit.git
```

d) Move into cloned directory
```bash
cd object_detection_streamlit
```
e) Now install all requirements
```bash
pip install -r requirements.txt
```
## Run
1. After successfull installation windows user can directly open the link that will be appeared
2. After successful installation open type
```bash
streamlit run final.py
 ```
and then open link 

## To Do
1. Add More Architecture Options
2. Add another loss functions options
3. More flexibility to choose parameters
4. Generated Video is not very much impressive , so correct it.



## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/pandeynandancse/object_detection_streamlit/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/pandeynandancse/object_detection_streamlit/issues/new). Please include sample queries and their corresponding results.


## Contribution
If you'd like to do some contribution, feel free to do so by opening a pull request [here](https://github.com/pandeynandancse/object_detection_streamlit/pulls). Please include sample queries and their corresponding results.




## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://i.imgur.com/jAyHARm.png" width=170>](https://www.streamlit.io/)
[<img target="_blank" src="https://i.imgur.com/OhpT4U4.jpg" width=170>](https://opencv.org/) 



## Contributor
[![Nandan Pandey](https://qph.fs.quoracdn.net/main-thumb-189737418-200-jmwzsixdznlgemnejuecomukeluqkgzd.jpeg)](https://pandeynandancse.github.io) |
-|
[Nandan Pandey](https://pandeynandancse.github.io) |)



## Credits
Special Thanks to Tensorflow for it's wonderful tutorial : https://www.tensorflow.org/tutorials/generative/style_transfer


 
