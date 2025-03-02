Readme

Introduction
This project aims to implement a Visual Question Answering (VQA) model capable of accurately interpreting both images and text to provide relevant answers. We use advanced deep learning techniques to handle complex interactions between visual and textual data, leveraging the VizWiz and VQAv2 datasets to evaluate and enhance the model’s performance.

File:
Here are the five Jupyter notebook files included in the submission, with brief descriptions:
	1.	1_Introduction_&_Data_Exploration.ipynb: This notebook provides an overview of the project and performs data exploration on the VizWiz and VQAv2 datasets. It 
	    includes visualizations and initial data analysis to understand key features and potential challenges.
	2.	2_Model_1_CLIP.ipynb: This notebook implements the first model using a pre-trained CLIP backbone. It covers feature extraction, model architecture design, and 
	    initial training results based on CLIP’s visual-textual embeddings.
	3.	2_Model_2_BLIP.ipynb: This notebook focuses on the second model, built using the BLIP (Bootstrapped Language-Image Pretraining) architecture. It details the model 
	    setup, fine-tuning process, and evaluation on both datasets.
	4.	4_Benchmark_1_VQA.ipynb: This notebook benchmarks the performance of the models on the VQAv2 dataset. It includes detailed evaluation metrics, comparisons with 
	    existing models, and analysis of model strengths and weaknesses.
	5.	4_Benchmark_2_GQA.ipynb: This notebook benchmarks the models on the GQA (Graph Question Answering) dataset. It highlights the model’s capability in handling graph- 
	    based reasoning tasks, with a focus on complex visual relationships.