# WHOS

**Weighted Histogram of Overlapping Stripes**

We have designed a discriminative and efficient descriptor of person appearance for re-identification based on coarse, striped pooling of local features. It exploits a simple yet effective center support kernel to approximately segment foreground from background. 

The entire descriptor construction process is illustrated in the following video (click on the image):

[![Watch the video](/media/descriptor.png | width=640)](https://www.youtube.com/watch?v=fkdraLVZYww)


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
>  year={2014},\
>  volume={PP},\
>  number={99},\
>  pages={1-1},\
>  doi={10.1109/TPAMI.2014.2369055},\
>  ISSN={0162-8828}\
>}

**Other papers related to this descriptor:**
- G. Lisanti , I. Masi , A. Del Bimbo, “Matching People across Camera Views using Kernel Canonical Correlation Analysis”, Eighth ACM/IEEE International Conference on Distributed Smart Cameras, 2014.
- S. Karaman, G. Lisanti, A. D. Bagdanov, A. Del Bimbo, “Leveraging local neighborhood topology for large scale person re-identification”, in Pattern Recognition, 2014.
- S. Karaman, G. Lisanti, A. D. Bagdanov, A. Del Bimbo, “From re-identification to identity inference: labelling consistency by local similarity constraints”, Advances in Computer Vision and Pattern Recognition: Person Re-Identification, 2014.
