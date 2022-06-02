*import tensorflow as tf  #this is used to import tensorflow for model creation and updating
	importing tensorflow library as name as tf
*import pandas as pd
	importing panda library as name as pd
*import numpy as np
	importing numpy library as name as tf

*import keras
	importing keras library for deep learning , learns on top of tensorflow

*import glob
	importing global library fot returning the file path

*train_files=glob.glob('C:/Users/ashut/Downloads/archive (1)/flowers/daisy/*')
	create variable name train_files to store the dataset in the list from the givin directry

*train_files
	you can see the whole list by running the train_files

*train_files[i]
	you can see the perticular item in the list using train_files[i]: where i is the order / list number-1
 
*import matplotlib.pyplot as plt
	importing the matplotlib.pyplot as name as plt

*from PIL import Image
	importing Image from PIL

*img1=Image.open(train_files[i])
	create a variable name img1 to store the ith index image from the list of trsin_files

*img1
	you can see the image the stored in the img1 

*img1_array=np.array(img1)
	creating the variable name as img1_array to store the convulation or colors in pixels matrics

*print( img1_array.shape)
	print the shape of img1_array

*print(img1_array)
	print the whole matrics of color pixel