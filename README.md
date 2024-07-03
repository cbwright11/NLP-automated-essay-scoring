# W266-Final-Project
Automated Essay Scoring Project

By: Collin Chee and Cameron Wright

This repository contains the code used to create an array of automated essay scoring (AES) models as well as the essay that summarizes the work. You can find the abstract below. The entire essay is labeled in the repository as `Final_Paper.pdf` and the code can be found in `Final_Notebook.ipynb`. 

We propose a two-stage model for AES: one stage which extracts relevant features from an essay, and another which uses those features to derive an over- all essay score. The two stages are trained on two separate datasets, the first of which pro- vides 6 scores for each essay (cohesion, syntax, vocabulary, phraseology, grammar, and conven- tions), the second of which provides just an overall essay score. We evaluate our model using Quadratic Weighted Kappa (QWK) as it is the reigning evaluation metric used in the field of AES. Several versions of each stage are explored and we report the final test QWK for each one. The version of our model that performed the best earned a test QWK score of 0.441 and is structured as follows: (stage 1) a BERT base model followed by a feed-forward neural network with 6 regression heads, (stage 2) a feed-forward neural network. Our work adds novelty to the AES field by offering a prompt independent approach to essay grad- ing. Further research could explore methods of receiving the essay prompt as an input to the grading system.



