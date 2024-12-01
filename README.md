## Passive Liveness Detection for Biometrics
Overview
This project focuses on Passive Liveness Detection, a crucial aspect of biometric security systems to prevent spoofing attacks. By distinguishing between real and fake inputs (e.g., photos, papercuts, prints, masks), the system ensures reliable facial recognition without requiring active user interaction.

<p align="center">
  <img src="prediction" >
</p>

### Dataset
The dataset contains diverse examples of facial images, including multiple ethnicities and spoofing attacks:

Real images: 826 samples

Fake images: 2,979 samples

### Types of spoofing attacks: Photos, Papercuts, Prints, Masks


Models and Performance
Model	Validation Accuracy	Test Accuracy	Inference Time (Per Image)
			
	
			

| Model     | Validation Accuracy | Test Accuracy | Inference Time |
|-----------|---------------------|---------------|--------------------|
| EfficientNet  | 99.08%         | 98.43%      | 0.0040 seconds  | 
| VGG16	   | 78.32%      |78.01%	             | 0.0007 seconds    | 
| ResNet50   | 96.06%       |95.29%    | 0.000184 seconds   |


### Key Features
#### Multi-Ethnicity Dataset: Covers diverse ethnic backgrounds for robust model performance.
#### Spoofing Attack Detection: Handles various attack types such as masks, photos, and prints.
#### State-of-the-Art Models: Comparison of EfficientNet, VGG16, and ResNet50 for performance benchmarking.
