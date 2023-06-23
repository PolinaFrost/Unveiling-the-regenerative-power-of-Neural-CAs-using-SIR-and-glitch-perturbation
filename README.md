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

Glitch perturb: This notebook can be run with two training setups, as described in the report. It is possible for the user to change the setup in this line: results = train(model, args, data=get_dataset(k=16,_url_id=0), mode='glitch'). If the mode argument is set to 'glitch', then the notebook will follow the improved training procedure described in the report, else it will use the standard training already present in the original implementation of the neural CA


