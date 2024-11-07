## MIDEFICS


#Project Overview
Model Base: We used #Idefics, an open-source reproduction of DeepMind's Flamingo model, as the foundation for this project.


Objective: Our goal was to fine-tune Idefics for medical conversational data to power a medical AI assistant capable of providing reliable and contextually accurate responses.


Fine-Tuning Process: We specifically focused on idefics-9b-instruct, applying #QLoRA to optimize the model. Training data was generated using open-source datasets from Kaggle and ISIC (International Skin Imaging Collaboration) alongside a custom pipeline, powered by GPT-3.5-turbo, to transform the data into a conversational format suitable for fine-tuning.


Evaluation: The fine-tuned model, named MIDEFICS, was rigorously evaluated using cutting-edge #LLM assessment techniques. Results showed a marked improvement in performance compared to the original idefics-9b-instruct model.


Model Calling Experimentation: Inspired by #GPT4's function calling capabilities, we explored “Model Calling” for MIDEFICS. This functionality allows the model to interface with image classification and object detection models, enhancing response accuracy and trustworthiness by integrating multimodal data.
