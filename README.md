# FAA_NLP
This repo contains the finetuning code of the whisper model with low-rank adaptation, a simple inference code, and a checkpoint of the trained whisper model. 

This link will give you access to the trained model checkpoint:
https://drive.google.com/file/d/1RqMqp-b_KYhVDxXDk6kOAezaZn8A9dU3/view?usp=sharing


Steps for Inference:

1) To do inference you have to install the following libraries.
  #!pip install datasets>=2.6.1
  #!pip install git+https://github.com/huggingface/transformers

2) Download the Checkpoint from the Google Drive link
  After downloading the checkpoint you can use Inference_whisper.py file
  You have to pass the address of the checkpoint in the designated locations in the inference code.
  You might have to import data according to your needs.

