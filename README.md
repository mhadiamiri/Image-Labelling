# Image-Labelling
This repo will give you a chance to familiarize yourself with Jupyter, scikit-learn and other
ML tools. You will use the Chars74K dataset of characters of the English alphabet. In particular,
you will be working with the images of characters and not with handwritten letters. The dataset
can be download from http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/ at the Center of
Vision, Speech and Signal Processing at the University of Surrey, Uk. You are looking for an
archive called EnglishImg.tgz, gzipped tar archive which you can extract with, e.g., gzip or
7-zip.
This archive contains a Bmp folder in EnglishImg/English/Img/GoodImg where you can and
62 subdirectories for each lower and upper case character in the latin alphabet (without accents)
and for the digits. The color images are of different size and contains background. The archive
also contains binary foreground-background masks in the Folder Msk for all images.
In this assignment, you will train binary and multiclass linear classifiers available from scikit-
learn on this dataset and evaluate the performance of these classifiers with various metrics.
