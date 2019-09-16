# YYSS
YouTube Yoga Summarization System

This repository contains the code, summaries and data belonging to the MBA Thesis 'Using Computer Vision for Unsupervised
Yoga Video Summarization'. 

The following folder structure is required on Google Drive before running the scripts;
 - Thesis
 -- Posinformation

The code can be executed by first loading the Thesis_1_Preprocessing.ipynb in Google Colab, picking a YouTube video ID and running the entire script.

Once done, script Thesis_2_Analyze_Preprocessed.ipynb can be loaded and executed in Colab to analyze the preprocessed files of step 1. The result will be a vertical and horizontal summary for each method (YYSS, Uniform sampling baseline, Shot boundary detection baseline).

As step one takes a long time, the two steps are separated so that tuning can happen in step 2 while analyzing a new video in step 1.
