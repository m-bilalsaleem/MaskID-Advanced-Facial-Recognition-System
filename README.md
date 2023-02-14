<h1>Face Mask Detection</h1>
Face Mask Detection System, which combines real-time computer vision with image processing techniques using OpenCV, PCA Unsupervised ML Algorithm (to reduce the dimensionality of data), and SVM Supervised ML Algorithm (to find the optimal hyperplane that separates the data into 2 classes; "Mask" and "Without Mask"). 80% of the original data is used to train the model while 20% is used to check model accuracy.
<hr>
<br>
<h2>Folder Contents</h2>
-> Main.ipynb<br>
-> Data Collection.ipynb      <i>(Project is developed by using my own created dataset of 200 images; with mask and without mask separately)</i><br>
-> data.xml      <i>(Haar feature classifiers (frontface), one of the components of Viola-Jones Object Detection Framework)</i><br>
-> with_mask.npy      <i>(Numpy Array of 200 images with mask)</i><br>
-> without_mask.npy      <i>(Numpy Array of 200 images without mask)</i><br>
-> img.jpg      <i>(A random image, used to explain the dimensions using OpenCV)</i>

<hr>
<br>
<h2>How to run the project</h2>
-> Upload the project to Jupyter Notebook<br>
-> (Optional) Run each cell of "Data Collection.ipynb", if you want to create your own dataset<br>
-> Run each cell of "Main.ipynb"<br>

<br>
Note: Make sure to place all files in one directory. Use "Escape" button to close the window.
 
