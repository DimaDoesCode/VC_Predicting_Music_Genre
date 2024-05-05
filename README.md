# CV <a id='predicting_music_genre'></a>
## Repository of the Deep Learning NLP and CV projects.

<b>Project Description</b>

<img src="https://github.com/DimaDoesCode/VC_Predicting_Music_Genre/blob/master/predicting_genre.jpeg" width="200" height="200" align="left"/>

This is a pet project aimed at practicing skills, acquiring new ones, and spending time in an engaging manner. It's evident that the design of a music album is somehow related to its content. But how closely? How can we confirm this based on data? And how could this be beneficial?
<br><br>
<b>Primary Objective</b>

The main goal is to develop a model that will classify the genre of a music album based on its cover image.

<b>Additional Objectives</b>

1. Clustering: Investigate which genres are more distinguishable from others and which are harder to separate.
2. MusicBrainz API: Expand the dataset with new images. It's possible to expand the list of genres and use the back side of the album cover.
3. OCR + NLP: Extract text from images and enhance the solution using NLP.
4. Create a miniature recommendation system based on images.
5. Utilize Streamlit to create a genre classifier or recommendation system as a web application.

<b>Data</b>

The data consists of images in PNG format packaged in zip archives. The name of each archive corresponds to a music genre. Each zip archive contains a folder with images of music album covers corresponding to that genre.

<b>Metrics</b>

For classification, metrics include Accuracy, Precision, Recall, and F1 score. Additional metrics can be proposed as part of the research.

<br>

---

<a href="https://github.com/DimaDoesCode/VC_Predicting_Music_Genre/blob/master/music_genre_baseline_v.0.9.ipynb"> To view the Jupyter Notebook code of the BaseLine research, click on this link.</a><br>
<a href="https://github.com/DimaDoesCode/VC_Predicting_Music_Genre/blob/master/music_genre_transfer_learning_v.0.4.ipynb"> To view the Jupyter Notebook code of the Transfer Learned ResNet50 model research, click on this link.</a><br>

<br>


| Project Name | Description | Libraries used |
| :---------------------- | :---------------------- | :---------------------- |
| Multilabel Purchases | TThe project aims to develop a model that will classify the genre of a music album based on its cover image. This project utilizes a ResNet50 Faiss and FastAI. | *python, sklearn, faiss, pytorch, torchvision, fastai and many others* |