---------------------------------------------------------------------
Tools Used:
1. Libraries: Python OpenCV, Ultralytics, seaborn, matplotlib.
2. Annotation of images: Roboflow
3. Model used:YOLOv8
---------------------------------------------------------------------
Methodology:

First I collected data from my phone gallery and which I imported in Roboflow for Data annotation.

Auto-annotation was used to detect and create box around people. Each images were checked for any manual annotation.

After checking all the data, they were converted to dataset ready to train our AI model. Jupyter Notebook was used in building the model.

Using the code snippet provided by Roboflow, it was copied in the notebook and the datasets were imported.

The challenging part was to find the data.yaml which will be imported once the code snippet runs. We should alter the dataset settings based on the location of data.yaml is present.

Then AI model is trained and tested using the test videos.
 
The graph is saved in the reports file.
