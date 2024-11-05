# NLP Project

## Comparative Evaluation of BART and T5 Models for Text Summarization Performance Analysis

This Repo contains a notebook that is used to finetune the popular text summarization model named T5 and BART on CNN Daily Mail dataset.<br>
**T5 (Text-To-Text Transfer Transformer)** is a popular text summarization model developed by Google. It was introduced in the paper titled "Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer" by Colin Raffel et al. in 2019. T5 is built on the Transformer architecture, which is known for its effectiveness in sequence-to-sequence tasks.<br>
**BART (Bidirectional and Auto-Regressive Transformers)** is a text generation model introduced by Facebook AI Research. It was presented in the paper titled "BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension" by Mike Lewis et al. in 2019. BART is built upon the Transformer architecture and is particularly effective in various text generation tasks, including text summarization. <br>

## Results  :
### Midterm Progress

| Experiment | Training dataset| Epochs | Rouge-1 | Rouge-2 | Rouge-l | Training Time |
|----------|----------|----------|----------|----------|----------|----------|
|   Original paper |   Full dataset  |   -  |   43.52  |   21.55  |   40.69  |   -  |
|   T5 |   1000  |   10  |   33  |   13.9  |   31.4  |   30 mins  |
|   T5 |   50000  |   3  |   31.31  |   13.1  |   29.69  |   12 hrs 20 min  |
|   T5  |   10000  |   3  |   32.9  |   14.9  |   31.5  |   2 hrs  |


## Loss vs epochs
![loss](https://github.com/bananighosh)

## Trained models

The trained model were large enough to store on github, so we have stored them on google drive which can be accessible on [Trained models](https://drive.google.com/drive/folders/1aIf-H1K9beieX5JNIslXHl-we2oE3KlW?usp=drive_link)

## Steps to run the notebook

Open colab and do run all, the notebook will run automatically producing all the results, no need of any furtherchanges.
