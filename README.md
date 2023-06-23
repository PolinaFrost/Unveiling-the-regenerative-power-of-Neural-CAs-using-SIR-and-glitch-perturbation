# Unveiling the regenerative power of Neural CAs using SIR and glitch perturbation
Natural Computing project by Benedetta Felici, Polina Moroza, Patrick van Beurden and Michiel Koenis.

# Dataset 
The data for this project is taken from the Kaggle "[Emoji] FULL EMOJI DATASET" which can be found at https://www.kaggle.com/code/subinium/emoji-full-emoji-dataset .
The images are taken from the Google folder: 102.png (demon mask), 1046.png (sled), 1064.png (heart) and 1142.png (accordion). The reason to explicitly mention is that throughout the projects we needed to multiple times to update the links to the images because they were getting deactivated. It is possible that when running this project the same can happen to you.

# Code
The code for this project is written in GoogleCollab. The reason for this is that the baseline implementation we use is implemented in GoogleCollab, and, more importantly, the notebook requires a lot of memory to run.

Baseline: https://colab.research.google.com/drive/1WO9-2Q_XV3fBDG_DeqMZpBfe6FBfWkqa?usp=sharing

Static perturb with SIR model: https://colab.research.google.com/drive/1GZlH95Fm6R8nTntsTaAeIifhe5mcKEdB?usp=sharing

Dynamic perturb with SIR model: https://colab.research.google.com/drive/1UnayQtYUOss-dF-70FFMaNDGE8-kmGH3?usp=sharing

Glitch perturb: https://colab.research.google.com/drive/1lqe4tHEmfy8WxJ7FZofF7TKwP0-aB5mi?usp=sharing

# Sample run
In the notebooks, the results of the last run are shown.

# Manual

At the top of each notebook resides a code block with several constants that can be adjusted to run different experiments. The most interesting parameter is probably `IMAGE_URL_ID`, which can be used to change the target image (0 for heart, 1 for demon, 2 for accordion and 3 for sled). From this point, it should be possible to run the experiment by clicking `Runtime -> Run all`. If an error is thrown, this is likely because the link to the respective image expired (see section Dataset).

