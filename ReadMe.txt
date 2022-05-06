I ran everything on Google Colab so I could utilize a GPU. Download these files and upload them
to your Google Drive. The code in colab will import these files. 

- Github Link: https://github.com/mcash8/Info-Theory-Project
|
|--- E2E Learning Experiments: Folder with colab links for E2E learning results
|-------|---MNIST_SaveActions.ipynb: Train FFNN on MNIST dataset and plot IP plots
|	|---IBnet_SaveActions.ipynb: Train FFNN on synthetic dataset and plot IP plots
|	|---utils: folder with support .py files needed for above .ipynb files
|	|---dataset.zip: needed of IBnet_SaveActions.ipynb
|
|--- CL Learning Experiments: Folder with colab links for CL learning results
|-------|---Cascade_SaveActions.ipynb: Train FFNN, cascade learning style on synthetic dataset
	|---Cascade_MNISTSaveActions.ipynb: Train FFNN, cascade learning style on MNIST dataset
	|---data_saving/[10,7,5,3]_experment_17: synthetic dataset for Cascade_SaveActions.ipynb
	|---utils: folder with support .py files needed 


Batch Gradient Descent: 
In E2E learning to train on whole batch you need to change  cfg['SGD_BATCHSIZE']
In CL learning to train on whole batch you need to change batch_size parameter in training_parmeters.py

Activation Functions:
In E2E learning to train on different activations you need to change  cfg['ACTIVATION']
In CL learning to train on different activations you need to change activation parameter in training_parmeters.py


Credits: 
On the Information Bottleneck Theory: https://github.com/artemyk/ibsgd
Information Bottleneck Theory Based Exploration of Cascade Learning: https://github.com/DorisxinDU/Information-Cascade