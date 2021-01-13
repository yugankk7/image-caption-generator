# image-caption-generator

This image caption generator uses deep learning models to generate captions for images.


This image caption generator was trained on the Flickr8k dataset and the Flickr8k text datasets. The dataset is available for free. You must complete a request form and the links to the dataset will be emailed to you. I would love to link to them for you, but the email address expressly requests: “Please do not redistribute the dataset“.
[REQUEST FORM FOR THE DATASET](https://forms.illinois.edu/sec/1713398)

You can also use a pre-trained model which can be found [here](https://drive.google.com/file/d/1VdLPDAoMZCcwY2_fq-MM2ns9Jc5w_T1C/view?usp=sharing).

Steps to run - 

1. Download the 2 datasets mentioned above and extract them in the same directory as that of the project.
2. Install "requiremnts.txt" using pip.
3. Run "create_features.py"
4. Run "create_descriptions.py"
You can skip step 5 if you downloaded the pre trained model from above and put it in the same directory.
5. Run "train.py"
6. Run "generate_description.py"
7. Profit?
