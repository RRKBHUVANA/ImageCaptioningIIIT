# ML-Image-Captioning-Models<br />
Automatic Image Captioning - Generating Descriptive Captions for Images, developed and submitted as part of IIIT Hyderabad, AI/ML Executive Post Graduation programme.<br />

**Team Members**:<br />
Kusal Degapudi<br />
Pradeep Reddy Pochareddy<br />
Raja Rama Krishna B<br />
Sai Nikhil Yanduri<br />

**Setting Environment**:<br />
Create below directory structure under Google MyDrive folder<br />
   ImageCaptioning<br />
     > Flicker8k<br />
       > Checkpoints<br />
       > Extracts<br />
         > Upload test_images.txt a file containing list of image names used for testing model<br />
         > Upload train_images.txt a file containing list of image names used for training model<br />
         > Upload val_images.txt a file containing list of image names used for validating model after each eporch<br />
         > Upload clip_vit_b32_embeddings.pkl a file containing clip image embedding<br />
         > Upload tokens.csv a file contains all token for given set of captions.<br />
       > Predictions<br />
       > Scores<br />
       > Upload images.zip 224X224 resized color 8k dataset<br />
       > Upload captions.csv file after curating the 8k dataset<br />
     > Flicker30<br />
       > Checkpoints<br />
       > Extracts<br />
         > Upload test_images.txt a file containing list of image names used for testing model<br />
         > Upload train_images.txt a file containing list of image names used for training model<br />
         > Upload val_images.txt a file containing list of image names used for validating model after each eporch<br />
         > Upload clip_vit_b32_embeddings.pkl a file containing clip image embedding<br />
         > Upload tokens.csv a file contains all token for given set of captions.<br />
       > Predictions<br />
       > Scores<br />
       > Upload images.zip 224X224 resized color 30k dataset<br />
       > Upload captions.csv file after curating the 30k dataset<br />

All the files under Extracts folder can be generated using Setups_ImageCaptioning_G7.ipynb colab notebooks
