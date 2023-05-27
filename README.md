# VSC
The code of Visual-semantic Consistency: A Mutual-reinforcing 3D Multi-modal Image Fusion Framework for Robust Lesion Segmentation<br>
<br>
# Task#1: Degradation-robust Autoencoder<br>
<br>
## To train:
*Prepare training data
*Run ```Python CUDA_VISIBLE_DEVICES=0 python tarin_dualSwinAE.py
# Task#2: Mutual-reinforcing Fusion<br>
<br>
## To train:
*Prepare training data
*Adjust ```PythonDualSwinAE_model_ptah``` in ```Python main.py``` to the path where you store the model in task #1.
*Run ```Python CUDA_VISIBLE_DEVICES=0 python tarin.py```
## To test:
*prepare test data
*Run ```Python CUDA_VISIBLE_DEVICES=0 python test.py```
This task is based on Task #1, so the code and models in task #1 should be downloaded and prepared in advance.
