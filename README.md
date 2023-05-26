# Sharif_WavLM
**for Speaker Verification**
----------------------------------------------------------------------------------------
In this repository, the wavLM model is used for quality and poor quality data for speaker verification task, and the PyCM library is used for evaluation.
## Table of Contents
1. [General Info](#general-info)
2. [How to Use](#how-to-use)
3. [Comparison](#comparison)
5. [Useful Links](#useful-links)
6. [Thanks to](#thanks-to)
## General Info
***
- **Datasets**: In this review, 30 speakers have been selected from the  [Farsdat Dataset](https://catalogue.elra.info/en-us/repository/browse/ELRA-S0380/),
  10 speakers is chosen for test as unknows and the rest of speakers as known (target/untarget) 
  each speakers has 10 audio files we use the first audio file as Enrollment file
  *audio files should be 6 secs (here we use ffmpeg to cut them)*
- **Evaluation**: For the evaluation part, the [PyCM](https://github.com/sepandhaghighi/pycm/tree/dev) library has been used, which is a reliable and comprehensive library and supports many metrics
  [PyCM](https://github.com/sepandhaghighi/pycm/tree/dev) is a multi-class confusion matrix library written in Python that supports both input data vectors and direct matrix, and a proper tool for post-classification model evaluation that    supports most classes and overall statistics parameters. PyCM is the swiss-army knife of confusion matrices, targeted mainly at data scientists that need a broad array of metrics for predictive models and accurate evaluation of a 
   large variety of classifiers.

- **System Config**: To fine-tune this model, [NVIDIA GeForce RTX 3060-12 GB](https://www.nvidia.com/nl-nl/geforce/graphics-cards/30-series/rtx-3060-3060ti/) is used.
- link to model: https://huggingface.co/SaraSadeghi/Sharif-WavLM

## How to Use
***
for high quality(microphone) data: use WavLM_base_AGP
for poor quality(telephony) data: use WavLM_base_telephony
## Comparison
***
Loading ....	:hourglass_flowing_sand:

## Useful Links
***
- Base Model:https://huggingface.co/microsoft/wavlm-base-plus-sd
- Base Paper:https://arxiv.org/abs/2110.13900
- [PyCM](https://github.com/sepandhaghighi/pycm/tree/dev)
## Thanks to
***
Thanks to [Sadra Sabouri](https://github.com/sadrasabouri) for his collaboration:handshake::handshake:

and also thanks to [PyCM](https://github.com/sepandhaghighi/pycm/tree/dev):fire::fire:
***

:star:**Give us a star if you found this repo useful.**

🙋‍♀️ **Open an issue if you have any comments about them.**

:smiling_face_with_three_hearts: **Feel free to open a pull request addding your feature. We'll be more than happy to accept them.**

