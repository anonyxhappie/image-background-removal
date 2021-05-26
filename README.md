# Portrait Segmentation using Tensorflow

This script removes the background from an input image. You can read more about segmentation [here](http://colab.research.google.com/github/tensorflow/models/blob/master/research/deeplab/deeplab_demo.ipynb)

### Setup
The script setup.sh downloads the trained model and sets it up so that the removebg.py script can understand. 
>	./setup.sh

### Running the script
> python3 -m venv venv
> . venv/bin/activate
> pip install -r requirements.txt

Go ahead and use the script as specified below, to execute fast but lower accuracy model:
>	python3 removebg.py image-1.jpg

For better accuracy, albiet a slower approach, go ahead and try :
>	python3 removebg.py image-1.jpg 1
