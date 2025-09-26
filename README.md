# Speech-Act-Analysis

This repository contains code and scripts used for analyzing speech acts in late-talking (LT) and typically developing (TD) children using the INCA-A coding scheme and a pretrained Conditional Random Field (CRF) model.

## Contents

- **Late_Talker_Speech_Act_Analysis.ipynb**  
  Jupyter Notebook used for the statistical analyses and visualizations of speech act distributions, group comparisons, and classification results.

- **Pre_processing_script_for_speech_act_CRF_model.ipynb**  
  Script that prepares and formats CHILDES transcript data into CSV files suitable for automated annotation with the CRF model.

- **command-line-code-crf-model.txt**  
  Example command-line code to run the pretrained CRF model from [childes-speech-acts](https://github.com/mitjanikolaus/childes-speech-acts) on the prepared CSV files to generate annotated outputs.
