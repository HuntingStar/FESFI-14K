![Uploading image.png…]()

Note:
1.	The annex will be used as support materials of this paper " Deep Learning-Empowered Single-Finger Tactile Device for Accessible Force/Position HCI in Upper-Limb Disabilities".
2.	These codes and videos are just for peer review and academic exchanges. Please don't make them for other commercial use without permission. If you are interested in our research work or have any questions, please do not hesitate to contact us.
3.	To comply with the journal’s page limit (less than ten pages) for the initial submission, some context of this paper has been made available at: https://github.com/HuntingStar/FESFI-14K. Specifically, these materials include Appendix A: SFTID Price list; Appendix B: loss function and MLP training performance with regional averages of position and 3D force in 12 zones; Appendix C: signal outputs and transmission characteristics of the three sensors; and Appendix D: game control mapping with SFTID adaptation. We will incorporate these materials into the revised manuscript following the first round of review.

Annex description
We use the Supplementary Materials to show more experimental details. The Supplementary Materials contains four files: Annex description, Appendixes, codes, and Supplementary Movie S1,2,3. The detailed file directory and description are shown as follows.

├─ Annex description.pdf          ## A basic introduction for this annex.
├─ Supplementary Movie S1,2,3    ## The video demonstrates the operation process of the 
trajectory experiment and two interactive games proposed in the paper.
├─ codes    ## Codes File. These codes are used to train the model proposed in this paper. 
├─ CNN     ## Model code for training model location coarse classification in SFTID location prediction
├─ MLP     ## This file is used to train the force/position accurate prediction model for                    
                  each region after the rough classification of the model in the SFTID position prediction.

Brief introduction about experimental codes:
Although all modules of the experiment have been carefully tested on our own computer, we cannot guarantee that the codes will function equally well on other platforms. It should be noted that some modules depend on specific system configurations and software versions. For instance, the CNN module requires Windows 11, Python 3.12 with PyTorch 2.6.0, and was trained on a single NVIDIA GeForce RTX 4070 GPU (4,608 CUDA cores, 12 GB VRAM) under CUDA 12. In addition, the visual perception and localization module occasionally crashes during execution, and the cause of this issue is not yet fully understood. At present, the codes represent an original version that may contain bugs. We are in the process of thoroughly checking, standardizing, and encapsulating them. A stable and published version will be made available on our GitHub repository in the future.
Contact
For further information and access to the dataset, please contact us at (wuyy363@mail2.sysu.edu.cn). The dataset is not publicly uploaded due to its large size and ongoing standardization, but access can be provided upon request via email.
