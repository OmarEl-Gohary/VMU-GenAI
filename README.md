#Stable Diffusion Model Trained on Our Selfies

This repository contains a fine-tuned version of the Stable Diffusion v1.5 model (pre-trained on runwayml/stable-diffusion-v1-5), which we customized by training on a dataset of our own selfies. Using Dreambooth training techniques, the model has been fine-tuned to generate AI images that closely resemble the faces and characteristics of our team members when given specific prompts.

Features

	•	Pre-trained model: Based on the robust runwayml/stable-diffusion-v1-5 model.
	•	Fine-tuned on personal data: Trained using selfies from our team, enabling it to generate images that resemble our likeness.
	•	Prompt-based generation: When inputting certain prompts or similar variations, the model generates AI images that mirror the fine-tuned data, producing outputs related to our training images.

Use Cases

	•	Input customized prompts that reflect certain attributes or descriptors from the training dataset, and the model will generate images close to our likeness.
	•	Explore how personalization of AI-generated content can be achieved by fine-tuning pre-trained models with specific, domain-specific data.

Technical Details

	•	Model: runwayml/stable-diffusion-v1-5
	•	Fine-tuning method: Dreambooth
	•	Frameworks: PyTorch, Hugging Face Diffusers
	•	Dataset: A curated collection of selfies from the team, used for personalized training.
