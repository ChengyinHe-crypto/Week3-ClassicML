## Assignment 3: Speech Emotion Recognition Via Machine Learning

The main goal of this assignment is to advance your comprehension of audio data classification modeling, building upon the previous task. You'll investigate diverse machine learning algorithms suitable for audio classification. In addition to the methods covered in the tutorial, try out supplementary techniques and approaches to enhance your model development. 

### Tasks: 

1. Fork the repositoryLinks to an external site. to your own account.
2. Perform audio data classification by training different machine learning models (as done in the tutorial) .
3. Test your model using the 1) RAVDESS test set, and 2) audio data you recorded from your prior assignment. Compare related metrics.
4. Compare scaled and unscaled versions. 
5. Commit changes to your own repository.
6. Create a detailed 1–2-page report on your results. Compare your results from your new data with the RAVDESS-only results you saw during the tutorial. Which model performed better in which test set? How did the scaled and unscaled versions differ in results? Discuss why you might have seen differences in them. Mention differences in features values of your data, and the RAVDESS data. Use screenshots from your code for results. Total analysis should be 1000 word limit, include images and graphs that shows your results. Cite all your resources, including the datasets as references (outside of page/word limit).
7. Upload your report on Canvas in PDF format, along with the link to your forked repository. This will provide a comprehensive overview of your exploration and application of various techniques in audio data classification modeling.

**Submission in Canvas:** 1) your GitHub account name and a link to your forked and changed repository, and 2) Upload your report on canvas in PDF format.

 

P.S.: Even if you fail to finalize the assignment, write down steps you took, issues you encountered and how you tried to solve them!

## Allan's experiment

The notebook `Assignment3_Audio_Classification.ipynb` follows the course feature-extraction and classic-ML workflow, compares raw, standard-scaled, and min-max-scaled features, and evaluates models on a RAVDESS holdout and Actor 25 recordings.

### Run locally

1. Install Python packages: `librosa`, `soundfile`, `numpy`, `pandas`, `matplotlib`, and `scikit-learn`.
2. Put the RAVDESS speech files in `Audio Data/Actor_01` through `Audio Data/Actor_24`.
3. Put the Actor 25 WAV files in `My Voice/Actor_25`.
4. Open and run `Assignment3_Audio_Classification.ipynb` from top to bottom.

The audio folders are intentionally not committed: RAVDESS is a separately distributed dataset, and Actor 25 contains personal voice recordings.
