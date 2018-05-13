# WHOS

**Weighted Histogram of Overlapping Stripes**

We have designed a discriminative and efficient descriptor of person appearance for re-identification based on coarse, striped pooling of local features. It exploits a simple yet effective center support kernel to approximately segment foreground from background. 

The entire descriptor construction process is illustrated in the following video (click on the image):

[![Watch the video](/media/descriptor.png)](https://www.youtube.com/watch?v=fkdraLVZYww)

**WHOS Descriptor:**

| Dataset |  |  |
|---|---|---|
| VIPeR | [HS+RGB+HOG](https://www.dropbox.com/s/ishg01gyj4ql3cq/VIPeR.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/l9khu2qxl5u6gca/VIPeR_ext.zip?dl=0) |
| CAVIAR4REID | [HS+RGB+HOG](https://www.dropbox.com/s/ktqud6fbhxt8wca/CAVIARa.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/ku9u3f2az0700z8/CAVIARa_ext.zip?dl=0) |
| i-LIDS | [HS+RGB+HOG](https://www.dropbox.com/s/obdus8e78ei694s/iLIDS.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/szmdwk8nzoqincn/iLIDS_ext.zip?dl=0) |
| ETHZ1 | [HS+RGB+HOG]() | [HS+RGB+Lab+HOG+LBP]() |
| ETHZ2 | [HS+RGB+HOG](https://www.dropbox.com/s/qom7egrawli6u4z/ETHZ2.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/fmcn05jxsjjt5n7/ETHZ2_ext.zip?dl=0) |
| ETHZ3 | [HS+RGB+HOG](https://www.dropbox.com/s/siy67n9otqa5nvk/ETHZ3.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/jof14inz2movrk4/ETHZ3_ext.zip?dl=0) |
| 3DPeS | [HS+RGB+HOG](https://www.dropbox.com/s/lt9xkpow1uhcf7y/3DPeS.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/97eylitxd7829oa/3DPeS_ext.zip?dl=0) |
| CUHK01 | [HS+RGB+HOG]() | [HS+RGB+Lab+HOG+LBP]() |
| PRID450s | [HS+RGB+HOG](https://www.dropbox.com/s/nu3b96tmyjb6q2v/prid_450s_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/p2dg3xpw54ykmbv/prid_450s_icdsc.mat.zip?dl=0) |
| GRID | [HS+RGB+HOG](https://www.dropbox.com/s/avxqzswuaaqnzqi/underground_reid_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/5ic59idve09ln1q/underground_reid_icdsc.mat.zip?dl=0) |
| Marker-1501 v15.09.15| [HS+RGB+HOG]() | [HS+RGB+Lab+HOG+LBP]() |

If you want to receive the descriptor extracted on a particular dataset please send me (giuseppe[dot]lisanti[at]unipv[dot]it) a zip file containing all the images with the following format:
```
PPPPPIIIIIIICCC.EEE
```
where:
- *PPPPP* represents the ID of the individual.
- *IIIIIII* represents the number of the image (of the cropped person image).
- *CCC* represents the number of the camera.
- *EEE* is the extesion; you can send me PNG, JPG, BMP (preferable PNG).

*The descriptor takes only 5ms to be extracted!*

**Please cite our paper if you use this descriptor:**
> @ARTICLE{LisantiPAMI14,\
>  author={Lisanti, G. and Masi, I. and Bagdanov, A. and Del Bimbo, A.},\
>  journal={Pattern Analysis and Machine Intelligence, IEEE Transactions on},\
>  title={Person Re-identification by Iterative Re-weighted Sparse Ranking},\
>  year={2015},\
>  volume={37},\
>  number={8},\
>  pages={1629-1642},\
>  doi={10.1109/TPAMI.2014.2369055},\
>  ISSN={0162-8828}\
>}

**Other papers related to this descriptor:**
- G. Lisanti , I. Masi , A. Del Bimbo, “Matching People across Camera Views using Kernel Canonical Correlation Analysis”, Eighth ACM/IEEE International Conference on Distributed Smart Cameras, 2014.
- S. Karaman, G. Lisanti, A. D. Bagdanov, A. Del Bimbo, “Leveraging local neighborhood topology for large scale person re-identification”, in Pattern Recognition, 2014.
- S. Karaman, G. Lisanti, A. D. Bagdanov, A. Del Bimbo, “From re-identification to identity inference: labelling consistency by local similarity constraints”, Advances in Computer Vision and Pattern Recognition: Person Re-Identification, 2014.
