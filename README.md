# ML-Image-Captioning-Models
Automatic Image Captioning - Generating Descriptive Captions for Images, developed and submitted as part of IIIT Hyderabad, AI/ML Executive Post Graduation programme.

**Team Members**:
Kusal Degapudi;
Pradeep Reddy Pochareddy;
Raja Rama Krishna B;
Sai Nikhil Yanduri

**Setting Environment**:
Create below directory structure under Google MyDrive folder
   ImageCaptioning
     > Flicker8k
       > Checkpoints
       > Extracts
         > Upload test_images.txt a file containing list of image names used for testing model
         > Upload train_images.txt a file containing list of image names used for training model
         > Upload val_images.txt a file containing list of image names used for validating model after each eporch
         > Upload clip_vit_b32_embeddings.pkl a file containing clip image embedding
         > Upload tokens.csv a file contains all token for given set of captions.
       > Predictions
       > Scores
       > Upload images.zip 224X224 resized color 8k dataset
       > Upload captions.csv file after curating the 8k dataset
     > Flicker30
       > Checkpoints
       > Extracts
         > Upload test_images.txt a file containing list of image names used for testing model
         > Upload train_images.txt a file containing list of image names used for training model
         > Upload val_images.txt a file containing list of image names used for validating model after each eporch
         > Upload clip_vit_b32_embeddings.pkl a file containing clip image embedding
         > Upload tokens.csv a file contains all token for given set of captions.
       > Predictions
       > Scores
       > Upload images.zip 224X224 resized color 30k dataset
       > Upload captions.csv file after curating the 30k dataset

All the files under Extracts folder can be generated using Setups_ImageCaptioning_G7.ipynb colab notebooks
