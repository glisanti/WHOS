# WHOS

**Weighted Histogram of Overlapping Stripes**

We have designed a discriminative and efficient descriptor of person appearance for re-identification based on coarse, striped pooling of local features. It exploits a simple yet effective center support kernel to approximately segment foreground from background. 

The entire descriptor construction process is illustrated in the following video (click on the image):

[![Watch the video](/media/descriptor.png)](https://www.youtube.com/watch?v=fkdraLVZYww)

**WHOS Descriptor:**

| Dataset |  |  |
|---|---|---|
| 3DPeS | [HS+RGB+HOG](https://drive.google.com/file/d/1H04BSUp8ithWKMwsUUVTrcmpUL_9WOi2/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1f8Tb60ecryVl4e_2R5iRoxMssO2Q85LB/view?usp=sharing) |
| CAVIAR4REID | [HS+RGB+HOG](https://drive.google.com/file/d/1tcFY7UiQs9DpBxEQQtvt5Fvls6fnZjQU/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1hmMmnLrvmTBBnmh-WtLfDDymoxYasjC7/view?usp=sharing) |
| CUHK01 | [HS+RGB+HOG](https://drive.google.com/file/d/1ZU536dEu810BAa6psYQWf-lVdWMXB26C/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/10VsJ-O0jfLy5BpWtUG5V8h6TmJd269Qr/view?usp=sharing) |
| CUHK03 | [HS+RGB+HOG](https://drive.google.com/file/d/1MLQlvydqpbz7X5uoCzcUhRdcbB9dOXkL/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1RP36EhDTwi7lgkIFkOqdcXVjPYjEJ8Bs/view?usp=sharing) |
| DukeMTMC-reID | [HS+RGB+HOG](https://drive.google.com/file/d/1jxOoUKFaQ-iRB8U5dHxcd4pH49nt-vdm/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1HZmvJtKrgKFrk671GIYqVx0tWMFkUX73/view?usp=sharing) |
| ETHZ1 | [HS+RGB+HOG](https://drive.google.com/file/d/1jWnh7wPnDqlZVrHq5S87h7PAJkjskCFw/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1L44OwssXSDvQG91vmBNdw7pA8opCnz4o/view?usp=sharing) |
| ETHZ2 | [HS+RGB+HOG](https://drive.google.com/file/d/1f6a6PkWevcMFZBorwaAzMSrhE60gkAkF/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/13CvngYB7WjfRlIVHYPPSzdNzhmqfVCrW/view?usp=sharing) |
| ETHZ3 | [HS+RGB+HOG](https://drive.google.com/file/d/1ssZeUaGH97JowWGHJZ712rd0O6eKaqTh/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1BXR8jkDoGRznPCbcaJumPKmV6peB4epC/view?usp=sharing) |
| i-LIDS | [HS+RGB+HOG](https://drive.google.com/file/d/1eYqcakD4sxLxgX9yUhPtVWo_snZLGJAA/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1u-LUImZjm4fRcRV42XUm8p6W36qn0k-p/view?usp=sharing) |
| GRID | [HS+RGB+HOG](https://drive.google.com/file/d/15IBSf_QaPYemmDy9ayo2WLZtEHJrOegi/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1kN_ZZFcHbvzC6KUy5Kx4UrszFxUtORD3/view?usp=sharing) |
| Market-1501 v15.09.15| [HS+RGB+HOG](https://drive.google.com/file/d/1WZBA5YvWlGI22b5qrwV6ekqlGkjHWr4h/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1EvoRmb-ekleVyP9cLzk6kAaMJM6fD1p1/view?usp=sharing) |
| PRID450s | [HS+RGB+HOG](https://drive.google.com/file/d/1HGDPLLqgqNQJM0xTxox20cKO5cumxHo8/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1VkuNPvqZGgZ84h21NXbXliqaMYASg2Fb/view?usp=sharing) |
| VIPeR | [HS+RGB+HOG](https://drive.google.com/file/d/1Lv7CNjDGPWxmDvNV0HQJKCStzihila6-/view?usp=sharing) | [HS+RGB+Lab+HOG+LBP](https://drive.google.com/file/d/1d3LuJNBSKXzNdIez9rBfK7gPfaFR6DWi/view?usp=sharing) |

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
