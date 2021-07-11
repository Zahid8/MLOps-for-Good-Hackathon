# COVID-19 Detection through Radiography images of Lung CT.
## _Contactless Covid Detection_



We have used the kaggle dataset : COVID-19 Radiography Dataset, which was procured by a team of researchers from Qatar University, Doha, Qatar, and the University of Dhaka, Bangladesh along with their collaborators from Pakistan and Malaysia in collaboration with medical doctors have created a database of chest X-ray images for COVID-19 positive cases along with Normal and Viral Pneumonia images. This COVID-19, normal and other lung infection dataset is released in stages. In the first release we have released 219 COVID-19, 1341 normal and 1345 viral pneumonia chest X-ray (CXR) images. In the first update, we have increased the COVID-19 class to 1200 CXR images. In the 2nd update, we have increased the database to 3616 COVID-19 positive cases along with 10,192 Normal, 6012 Lung Opacity (Non-COVID lung infection) and 1345 Viral Pneumonia images. We will continue to update this database as soon as we have new x-ray images for COVID-19 pneumonia patients.

The dataset consists of:

COVID-19 data: COVID data are collected from different publicly accessible dataset, online sources and published papers. -2473 CXR images are collected from padchest dataset. -183 CXR images from a Germany medical school. -559 CXR image from SIRM, Github, Kaggle & Tweeter -400 CXR images from another Github source.

Normal images: 10192 Normal data are collected from from three different dataset. -8851 RSNA -1341 Kaggle

Lung opacity images: 6012 Lung opacity CXR images are collected from Radiological Society of North America (RSNA) CXR dataset

Viral Pneumonia images: 1345 Viral Pneumonia data are collected from the Chest X-Ray Images (pneumonia) database

Saved Model File : https://drive.google.com/file/d/1VazjtXP3cS6iSHJ-ohP19Adu2bXxTV4V/view?usp=sharing

## Features

- Upload a Lung CT image and get instant predictions




## Tech


- [Python] - Python is a programming language that lets you work quickly and integrate systems more effectively.
- [Tensorflow] - TensorFlow is a free and open-source software library for machine learning.
- [Numpy] - NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
- [Matplotlib] - Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy.
- [Keras] - Keras is an open-source software library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library. 
- [Streamlit] - Streamlit turns data scripts into shareable web apps. 

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## How to use it


#### Get the code
```
$ git clone https://github.com/Zahid8/MLOps-for-Good-Hackathon.git
$ cd MLOps-for-Good-Hackathon
```
##### Download the saved model from [here](https://drive.google.com/file/d/1VazjtXP3cS6iSHJ-ohP19Adu2bXxTV4V/view?usp=sharing) and paste it into the same directory as the cloned git repository.

#### Virtualenv modules installation (Unix based systems)
```
$ virtualenv env
$ source env/bin/activate
```
#### Virtualenv modules installation (Windows based systems)
```
$ # virtualenv env
$ # .\env\Scripts\activate
```
#### Install modules
```
$ pip3 install -r requirements.txt
```
#### Run the WebApp
```
$ streamlit run rps_app.py
```






## License


##### Open Source, Hell Yeah!
