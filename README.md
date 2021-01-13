# image-caption-generator

This image caption generator was trained on the Flickr8k dataset which can be found [here](https://www.kaggle.com/adityajn105/flickr8k) and the Flickr8k test which can be found [here](https://www.kaggle.com/riya786/flickr8k-text). If you would like to train your own model, please download the following two datasets.

You can also use a pre-trained model which can be found [here](https://drive.google.com/file/d/1VdLPDAoMZCcwY2_fq-MM2ns9Jc5w_T1C/view?usp=sharing]

Steps to run - 

1. Download the 2 datasets mentioned above and extract them in the same directory as that of the project.
2. Run "create_features.py"
3. Run "create_description.py"
You can skip step 4 if you downloaded the pre trained model from above and put it in the same directory.
4. Run "train.py"
5. Run "generate_description.py"
6. Profit?
