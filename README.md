# ML-Image-Captioning-Models<br />
Automatic Image Captioning - Generating Descriptive Captions for Images, developed and submitted as part of IIIT Hyderabad, AI/ML Executive Post Graduation programme.<br />

**Team Members**:<br />
Kusal Degapudi<br />
Pradeep Reddy Pochareddy<br />
Raja Rama Krishna B<br />
Sai Nikhil Yanduri<br />

**Setting Environment**:<br />
Create below directory structure under Google MyDrive folder<br />
&nbsp;&nbsp;&nbsp;ImageCaptioning<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Flicker8k<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Checkpoints<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Extracts<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload test_images.txt a file containing list of image names used for testing model<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload train_images.txt a file containing list of image names used for training model<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload val_images.txt a file containing list of image names used for validating model after each eporch<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload clip_vit_b32_embeddings.pkl a file containing clip image embedding<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload tokens.csv a file contains all token for given set of captions.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Predictions<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Scores<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload images.zip 224X224 resized color 8k dataset<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload captions.csv file after curating the 8k dataset<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Flicker30k<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Checkpoints<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Extracts<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload test_images.txt a file containing list of image names used for testing model<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload train_images.txt a file containing list of image names used for training model<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload val_images.txt a file containing list of image names used for validating model after each eporch<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload clip_vit_b32_embeddings.pkl a file containing clip image embedding<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload tokens.csv a file contains all token for given set of captions.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Predictions<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Scores<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload images.zip 224X224 resized color 30k dataset<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>&nbsp;Upload captions.csv file after curating the 30k dataset<br />

All the files under Extracts folder can be generated using Setups_ImageCaptioning_G7.ipynb colab notebooks
