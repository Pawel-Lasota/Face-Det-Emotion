How to run the AI product:

1. Navigate to the product folder
2. Inside the product folder, open the folder in visual studio code
3. Open FaceExpressionRec.ipynb as a Jupyter notebook file
4. Download the necessary libraries, e.g. by uncommenting the embedded code.

Required Libraries: tensorflow, pandas, opencv-python, mtcnn, matplotlib, scikit-learn

5. Press run all to run the entire code. The pre-processing of dataset images takes approximately 10 minutes, the rest is extremely quick.






How to run the UI:

This can be ran before the AI product as the model is already in the file as .h5. If not working then run the AI and then run the UI.

1. Open RoboticsExpressionUI in visual studio code as a Jupyter Notebook
2. Download the necessary libraries, e.g. by uncommenting the embedded code.

Required libraries: Pillow, opencv-python, keras, tensorflow, mtcnn

3. Press run all
4. Upload any image from 'black-box testing images' folder or 'random images to try' folder
5. The UI should output the key region of interest in the image and the confidence levels of predictions
