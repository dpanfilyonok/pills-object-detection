﻿
-   `annotations`: This folder will be used to store all  `*.csv`  files and the respective TensorFlow  `*.record`  files, which contain the list of annotations for our dataset images.
    
-   `images`: This folder contains a copy of all the images in our dataset, as well as the respective  `*.xml`  files produced for each one, once  `labelImg`  is used to annotate objects.
    
    -   `images\train`: This folder contains a copy of all images, and the respective  `*.xml`  files, which will be used to train our model.
    -   `images\test`: This folder contains a copy of all images, and the respective  `*.xml`  files, which will be used to test our model.
    
-   `pre-trained-model`: This folder will contain the pre-trained model of our choice, which shall be used as a starting checkpoint for our training job.
    
-   `training`: This folder will contain the training pipeline configuration file  `*.config`, as well as a  `*.pbtxt`  label map file and all files generated during the training of our model.
    
-   `README.md`: This is an optional file which provides some general information regarding the training conditions of our model. It is not used by TensorFlow in any way, but it generally helps when you have a few training folders and/or you are revisiting a trained model after some time.
