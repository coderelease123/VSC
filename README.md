# VSC
The code of Visual-semantic Consistency: A Mutual-reinforcing 3D Multi-modal Image Fusion Framework for Robust Lesion Segmentation
<br>
# Training:<br>
## Stage#1: Degradation-robust Autoencoder<br>
* Prepare training data<br>
* Run ```CUDA_VISIBLE_DEVICES=0 python tarin_dualSwinAE.py```<br>
##  Stage#2: Mutual-reinforcing Fusionr<br>
* Prepare training data<br>
* Adjust ```DualSwinAE_model_ptah``` in ```train.py``` to the path where you store the model in task #1.<br>
* Run ```CUDA_VISIBLE_DEVICES=0 python tarin.py```<br>
# Test:<br>
* Prepare test data<br>
* Run ```CUDA_VISIBLE_DEVICES=0 python test.py```<br>
▢ This task is based on Stage #1, so the code and models in Stage #1 should be downloaded and prepared in advance.<br>  
