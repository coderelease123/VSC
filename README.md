# VSC
The code of Visual-semantic Consistency: A Mutual-reinforcing 3D Multi-modal Image Fusion Framework for Robust Lesion Segmentation
<br>
# Task#1: Degradation-robust Autoencoder<br>
## To train:<br>
* Prepare training data<br>
* Run ```Python CUDA_VISIBLE_DEVICES=0 python tarin_dualSwinAE.py```<br>

# Task#2: Mutual-reinforcing Fusionr<br>
## To train:<br>
* Prepare training data<br>
* Adjust ```Python DualSwinAE_model_ptah``` in ```Python train.py``` to the path where you store the model in task #1.<br>
* Run ```Python CUDA_VISIBLE_DEVICES=0 python tarin.py```<br>
## To test:<br>
* prepare test data<br>
* Run ```Python CUDA_VISIBLE_DEVICES=0 python test.py```<br>
This task is based on Task #1, so the code and models in task #1 should be downloaded and prepared in advance.<br>  
