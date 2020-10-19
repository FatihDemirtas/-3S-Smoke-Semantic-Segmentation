## Smoke detection via semantic segmentation U-Net model and image augmentation in Keras

The main purpose of this use-case is to detect smoke in any background. The smoke can also have variations regarding its source, color, environment etc. We should be able to semantically segment smoke to analyze it's various features like color, intensity, duration of ejection of smoke (from video feed), etc.

---
## U-Net
The U-Net is a convolutional neural network that was developed for biomedical image segmentation at the Computer Science Department of the University of Freiburg, Germany. The network is based on the fully convolutional network and its architecture was modified and extended to work with fewer training images and to yield more precise segmentations.

---
## Installation

Create a new conda environment:

	-- conda create --name semantic python==3.7

Install required libraries:

	-- pip install -r requirements.txt

Necessary Nvidia-Driver:

	-- 430.64 or higher

Necessary Cuda version:
	
	-- Cuda 10.1 V 10.1.105 or higher

Necessary CuDnn version:

	-- CUDNN_MAJOR 7
	-- CUDNN_MINOR 6
	-- CUDNN_PATCHLEVEL 4


