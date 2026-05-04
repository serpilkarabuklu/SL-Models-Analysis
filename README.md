# Targeted Linguistics Analysis of Sign Language Models with Minimal Translation Pairs
This repository contains research code, the dataset (ASL-MTP), and analysis scripts for the paper [Targeted Linguistics Analysis of Sign Language Models with Minimal Translation Pairs](http://arxiv.org/abs/2604.27232). 

<img src="images/fig1.png" width="600" alt="Figure 1" />

Models of sign language have historically lagged behind those for spoken language (text and speech). Recent work has greatly improved their performance on tasks like sign language translation and isolated sign recognition. However, it remains unclear to what extent existing models capture various linguistic phenomena of sign language, and how well they use cues from the multiple articulators used in sign language (hands, upper body, face). We introduce a new benchmark dataset for American Sign Language, ASL Minimal Translation Pairs (ASL-MTP), divided into multiple types of sign language phenomena and corresponding minimal pairs of translations, for performing such linguistic analyses. As a case study, we use ASL-MTP to analyze a state-of-the-art ASL-to-English translation model. We conduct a targeted analysis of the model by ablating various input cues during training and inference and evaluating on the phenomena in ASL-MTP. Our results show that, while the model performs above chance level on most of the phenomena, it relies strongly on manual cues while often missing crucial non-manual cues.

----
## Usage
### 1. ASL-MTP

The benchmark (ASL-MTP) is in [dataset](dataset/).

### 2. Model

The details about SHuBERT, its training, and experiments are in [experiments](experiments/).

### 3. Statistical Analysis

The analysis scripts and results are in [analysis](analysis/).

----
## Citing our work
If you find our work useful in your research, please consider citing:

```bibtex
@misc{karabüklü2026targetedlinguisticanalysissign,
      title={Targeted Linguistic Analysis of Sign Language Models with Minimal Translation Pairs}, 
      author={Serpil Karabüklü and Kanishka Misra and Shester Gueuwou and Diane Brentari and Greg Shakhnarovich and Karen Livescu},
      year={2026},
      eprint={2604.27232},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2604.27232}, 
}
```
