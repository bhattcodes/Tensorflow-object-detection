# Tensorflow-object-detection

- Architecture : SSD MobileNet v2 FPN Lite 320x320
- Tensorflow Object Detection API
- Custom DataSet used
- labelImg: used for creating annotation.

## Steps

Step 1: Clone this repo https://github.com/bhattcodes/Tensorflow-object-detection </br>
Step 2: Create New Virtual Env</br>
<pre>python -m venv tfod</pre>
Step 3: Activate your Virtal Env</br>
<pre>source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows` </pre>
Step 4: Install dependencies and add virtual env to the Python Kernel</br>
<pre>`python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj`</pre>
Step 5: Run this notebook,<a href= https://github.com/bhattcodes/Tensorflow-object-detection/blob/master/1.%20Image%20Collection.ipynb>1. Image Collection.ipynb</a> </br>
Step 6: Manually divide the test and train images with their annotations (here i used pascal VOC xml) for training.</br>
<pre>.\Tensorflow\workspace\images\train
.\Tensorflow\workspace\images\test</br></pre>
Step 7: Run this notebook now and follow the process step by step,<a href= https://github.com/bhattcodes/Tensorflow-object-detection/blob/master/2.%20Training%20and%20Detection.ipynb>2. Training and Detection</a></br>
Step 8: Train the model, on local machine or collab, works on both, You will see the loss metrics
Step 9: Run the trained model, To predict from images and well as Live from Webcam.
