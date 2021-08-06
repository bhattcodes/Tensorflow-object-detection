# Tensorflow-object-detection

## Steps

Step 1: Clone this repo https://github.com/bhattcodes/Tensorflow-object-detection </br>
Step 2: Create New Virtual Env</br>
`python -m venv tfod`</br>
Step 3: Activate your Virtal Env</br>
`source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows` </br>
Step 4: Install dependencies and add virtual env to the Python Kernel</br>
`python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj`</br>
Step 5: Run this notebook, https://github.com/bhattcodes/Tensorflow-object-detection/blob/master/1.%20Image%20Collection.ipynb
Step 6: Manually divide the test and train images with their annotations (here i used pascal VOC xml) for training.</br>
.\Tensorflow\workspace\images\train</br>
.\Tensorflow\workspace\images\test</br>
Step 7: Run this notebook now and follow the process step by step, https://github.com/bhattcodes/Tensorflow-object-detection/blob/master/2.%20Training%20and%20Detection.ipynb</br>
Step 8: Train the model, on local machine or collab, works on both, You will see the loss metrics
Step 9: Run the trained model, To predict from images and well as Live from Webcam.
