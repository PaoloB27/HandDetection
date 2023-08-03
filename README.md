# HandDetection
## Brief description
The project consists in a software that recognizes hands in images and then performs instance segmentation.
The main parts of the system are:
- training of a Yolo deep neural network to detect hands in images;
- segmentation of the hand in each bounding box through old-style computer vision segmentation techniques.
## Brief discussion on the results
The results of the detection of hands are very good and confirm that NN's are the best way of solving such a problem.
Regarding segmentation, we know that with CNN's we could have obtained much better results, but the thing is that we wanted to put into practice the old-style techniques discussed during the lectures of the computer vision course. Actually, the results are still good if we consider the heterogeneity of the dataset, which contains hands of different shapes and dimensions, in differnt positions, with different backgrounds and of different colors.
## Link to last trained weights and dataset used for the training
https://drive.google.com/drive/folders/1OH6gFzy8r82F2DVXrzTuOyVrsmGgOZaW?usp=share_link
The file with the weights has to be placed in the folder NN.
## Results folder
The folder contains the output results of our algorithm applied to some unseen images.
