# Build-a-Docker-Container-to-Perform-Batch-Serving-of-ML-model

Link:

https://towardsdatascience.com/build-and-run-a-docker-container-for-your-machine-learning-model-60209c2d7a7f

You need the following files:

● Dockerfile

● Train.py

● Inference.py


This is the EEG brainwave data that has been processed using statistical extraction.
There are totally 1300 rows and 162 columns in the train dataset. The feature Letter is
used as the target column. It has 26 classes which is a representation of the 26
alphabets.

Task:

train.py
1. Add one more model apart from the one used (any machine
learning model of your choice) in the train.py file and save it. 
2. Modify the inference.py file to display the output of the above model. 
3. Build the docker image of the final application and run it and submit the
screenshot of the output. 
a. Build the Docker File
b. Run the docker container
c. Save the screenshot of the output and submit it.

=====================================================================

Command to build the docker image in bash terminal: 

docker buildx build -t docker-ml-model -f Dockerfile .

docker run docker-ml-model python3 inference.py

=====================================================================
