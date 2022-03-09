# Contains my Machine Learning Journey from the Start

Hi!!!
I have categorized all my notebooks on Image Processing, Natural Language Processing and everything else into different folders all in one place and not lying all over on Github.

## [Image Processing and Research](https://github.com/SOUMEE2000/Machine-Learning-Stash/tree/main/1.%20Image%20Processing%20Basics%20and%20Research)

* **[1. Starting_out](https://github.com/SOUMEE2000/Machine-Learning-Stash/blob/main/Image%20Processing%20Basics/1.%20Starting_out.ipynb)**: The very basics of image processing like colour channels, separating them, frequency histograms, and stuff like that while I was starting out

* **[2. U-Net.ipynb](https://github.com/SOUMEE2000/Machine-Learning-Stash/blob/main/Image%20Processing%20Basics/2.%20U_Net.ipynb)**:
The U-net on the DRIVE Dataset and the results are saved in the above folder.

* **[3. Dendritic Spine Segmentation](https://github.com/SOUMEE2000/Machine-Learning-Stash/blob/main/Image%20Processing%20Basics/3.%20Dendritic_spine_segmentation(U_Net).ipynb)**: Transfer Learning was applied to images of dendritic spines. The same DRIVE Dataset was modified a bit(the images were negated to suit the needs of another dataset where the objects were of high intensity and background was of low intensity) and trained on the same UNet to segment out the dendritic spines from the different dataset.

* **[4. Dendritic Spine Segmentation](https://github.com/SOUMEE2000/Machine-Learning-Stash/blob/main/Image%20Processing%20Basics/4.%20Dendritic_Spine_Segmentation(Attention%20U_Net).ipynb)** : The same as the above notebook but with the attention model (reference: Python for Microscripts repo). A concensus based algorithm was used for binarisation of the input images in dendritic spines and the model was trained on the image pair generated with it.

* **[5. Disease Prediction from Medical Imaging( non-intrusive tests )](https://github.com/SOUMEE2000/Machine-Learning-Stash/blob/main/1.%20Image%20Processing%20Basics%20and%20Research/5.%20Disease_prediction_from_medical_imaging(non_intrusive_tests).ipynb)** : A part of research at University of Hyderabad, where I had tried to make a tool which would take in various images like a person's face and drawings and predict what diseases they might possibly have. The models used are really simple. This project however is no longer being actively worked on. Thorough literature reviews and datasets used are included in **[Additional Material](https://github.com/SOUMEE2000/Machine-Learning-Stash/tree/main/1.%20Image%20Processing%20Basics%20and%20Research/Additional%20Material%20(%20with%20the%205th%20notebook%20))**

