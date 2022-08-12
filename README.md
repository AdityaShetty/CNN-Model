
# Identical Meme Classification: A Neural network approach
<hr>

The project aims to test the existing neural network algorithm for image classification of Meme images such as muffin and chihuaha dogs which are very similar to each other.

<img src="http://sanjay.ie/aditya/meme.jpg" height="300"/>

## Setting up python notebook

-> Open your Google Drive

-> Upload the .ipynb file > Open with > Google Colaboratory  

## GPU Setting

Edit > Notebook settings or Runtime>Change runtime type and select GPU as Hardware accelerator

#### Install Libraries :

Google Colab is built for running Machine Learning projects hence has most of the libraries installed, but for assurance we can copy paste the entire list of libraries below and install them at a go.

`!pip install` or `!apt-get install`

```http
#Must install before running
!pip install colorama

#These libraries do exist in colab, but you can reinstall them if required
!pip3 install tensorflow==1.8
!pip3 install keras
!pip3 install torch torchvision
!apt-get install python-numpy python-scipy
!pip install os
!pip install math
!pip install shutil
```
### After the setup is ready, run all the code chunks together

<img src="http://sanjay.ie/aditya/Process.gif" height="400"/>

### GUI : Predicting the Image

At the very end of the notebook, GUI will automatically run for testing, here you can upload a meme image from your local server/desktop and check the accuracy. You can download the dataset from the repository.

<img src="http://sanjay.ie/aditya/GUI.gif" height="400"/>

You can run this block as many times you want to test the images. The prediction/result will be displayed below the image with the calculated probability.

*The entire notebook will take 12-15 minutes to run all blocks in GPU environment.*


