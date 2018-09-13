# WHOS

**Weighted Histogram of Overlapping Stripes**

We have designed a discriminative and efficient descriptor of person appearance for re-identification based on coarse, striped pooling of local features. It exploits a simple yet effective center support kernel to approximately segment foreground from background. 

The entire descriptor construction process is illustrated in the following video (click on the image):

[![Watch the video](/media/descriptor.png)](https://www.youtube.com/watch?v=fkdraLVZYww)

**WHOS Descriptor:**

| Dataset |  |  |
|---|---|---|
| 3DPeS | [HS+RGB+HOG](https://www.dropbox.com/s/lt9xkpow1uhcf7y/3DPeS.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/97eylitxd7829oa/3DPeS_ext.zip?dl=0) |
| CAVIAR4REID | [HS+RGB+HOG](https://www.dropbox.com/s/ktqud6fbhxt8wca/CAVIARa.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/ku9u3f2az0700z8/CAVIARa_ext.zip?dl=0) |
| CUHK01 | [HS+RGB+HOG](https://www.dropbox.com/s/xvvorbc0fup135q/CUHK01_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/y8a6b5i73liwqv6/CUHK01_icdsc.mat.zip?dl=0) |
| CUHK03 | [HS+RGB+HOG](https://www.dropbox.com/s/bjvu549ydqvrg9c/CUHK03img_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/z5ievzar3sf89gq/CUHK03img_icdsc.mat.zip?dl=0) |
| DukeMTMC-reID | [HS+RGB+HOG](https://www.dropbox.com/s/swyx5ojlfij1hau/DukeMTMC-reID_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/ubkj0v16ftv6g36/DukeMTMC-reID_icdsc.mat.zip?dl=0) |
| ETHZ1 | [HS+RGB+HOG](https://www.dropbox.com/s/phiab5aw8ddssbx/ETHZ1.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/uvfvl0u1bru064m/ETHZ1_ext.zip?dl=0) |
| ETHZ2 | [HS+RGB+HOG](https://www.dropbox.com/s/qom7egrawli6u4z/ETHZ2.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/fmcn05jxsjjt5n7/ETHZ2_ext.zip?dl=0) |
| ETHZ3 | [HS+RGB+HOG](https://www.dropbox.com/s/siy67n9otqa5nvk/ETHZ3.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/jof14inz2movrk4/ETHZ3_ext.zip?dl=0) |
| i-LIDS | [HS+RGB+HOG](https://www.dropbox.com/s/obdus8e78ei694s/iLIDS.mat_.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/szmdwk8nzoqincn/iLIDS_ext.zip?dl=0) |
| GRID | [HS+RGB+HOG](https://www.dropbox.com/s/avxqzswuaaqnzqi/underground_reid_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/5ic59idve09ln1q/underground_reid_icdsc.mat.zip?dl=0) |
| Market-1501 v15.09.15| [HS+RGB+HOG](https://www.dropbox.com/s/spicz8ike37cxgi/Market-1501-v15.09.15_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/0d4vo1s2c44z3d9/Market-1501-v15.09.15_icdsc.mat.zip?dl=0) |
| PRID450s | [HS+RGB+HOG](https://www.dropbox.com/s/nu3b96tmyjb6q2v/prid_450s_pami.mat.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/p2dg3xpw54ykmbv/prid_450s_icdsc.mat.zip?dl=0) |
| VIPeR | [HS+RGB+HOG](https://www.dropbox.com/s/ishg01gyj4ql3cq/VIPeR.zip?dl=0) | [HS+RGB+Lab+HOG+LBP](https://www.dropbox.com/s/l9khu2qxl5u6gca/VIPeR_ext.zip?dl=0) |

If you want to receive the descriptor extracted on a particular dataset please send me (giuseppe[dot]lisanti[at]unipv[dot]it) an email.

**Please cite our paper if you use this descriptor:**
> @ARTICLE{LisantiTPAMI15,\
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
