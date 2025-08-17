<img width="419" height="257" alt="image" src="https://github.com/user-attachments/assets/49616354-e474-428f-a42f-ce5a70040e87" />


Note:
1.	The annex will be used as support materials of this paper " Deep Learning-Empowered Single-Finger Tactile Device for Accessible Force/Position HCI in Upper-Limb Disabilities".

2.	These codes and videos are just for peer review and academic exchanges. Please don't make them for other commercial use without permission. If you are interested in our research work or have any questions, please do not hesitate to contact us.

Annex description
We use the annex to show more experimental details. The annex contains Three files: codes, video.mp4 and Appendixex. The detailed file directory and description are shown as follows.

├─ Annex description.pdf               ## A basic introduction for this annex.

├─ Appendixes.pdf               ## Supplementary information for the paper

├─ video.mp4      ## The video demonstrates the operation process of the trajectory experiment and two interactive games proposed in the paper.

├─ codes    ## Codes File. These codes are used to train the model proposed in this paper. 

├─ CNN     ## Model code for training model location coarse classification in SFTID location prediction

├─ MLP     ## This file is used to train the force/position accurate prediction model for                    
                  each region after the rough classification of the model in the SFTID position prediction.

Brief introduction about experimental codes:
Although all modules of the experiment have been carefully tested in our computer, we are very sorry that we cannot guarantee that these codes can work well on other platform. It should be noted that some modules require special dependencies and system version. For example, "CNN" module requires: Windows11, Python 3.12 with PyTorch 2.6.0 and trained on a single NVIDIA GeForce RTX 4070 GPU (4,608 CUDA cores, 12-GB VRAM) under CUDA 12. Additionally, visual perception and location module sometimes crashes suddenly in the middle of running, and we are not sure that why it happens. In fact, these codes are just the original version and we are very sorry for some bugs. We are trying to thoroughly check, standardize and encapsulate these codes of this experiment. Later, we will upload them and provide a published and stable version in our Github.

Contact
For more information and access to datasets please contact us (wuyy363@mail2.sysu.edu.cn).
