# Hyperspectral Image Classification

This repository implementates the Deep Double-Channel Dense Network (DDCD) for hyperspectral image classification based on PyTorch and sklearn.

The detailed results can be seen in the [A Deep Double-Channel Dense Network for Hyperspectral Image Classification](None).

The training and testing code can be seen in [Double-Branch-Dual-Attention-Mechanism-Network](https://github.com/lironui/Double-Branch-Dual-Attention-Mechanism-Network).

If our code is helpful to you, please cite
`Wang K., Zheng, S., Li, R. *, Gui L. A Deep Double-Channel Dense Network for Hyperspectral Image Classification. Journal of Geodesy and Geoinformation Science (JGGS).`
`Li R, Zheng S, Duan C, et al. Classification of Hyperspectral Image Based on Double-Branch Dual-Attention Mechanism Network[J]. Remote Sensing, 2020, 12(3): 582.`


Requirements：
------- 
```
numpy >= 1.16.5
PyTorch >= 1.3.1
sklearn >= 0.20.4
```

Datasets:
------- 
You can download the hyperspectral datasets in mat format at: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes.

Network:
------- 

![network](https://github.com/lironui/Double-Branch-Dual-Attention-Mechanism-Network/blob/master/figures/Figure%206.%20The%20structure%20of%20the%20DBDA%20network.png)  
Figure 1. The structure of the DBDA network. The upper Spectral Branch composed of the dense 
spectral block and channel attention block is designed to capture spectral features. The lower Spatial 
Branch constituted by dense spatial block, and spatial attention block is designed to exploit spatial 
features. 

Results:
------- 
![IP](https://github.com/lironui/Double-Branch-Dual-Attention-Mechanism-Network/blob/master/figures/Figure%209.%20Classi%EF%AC%81cation%20maps%20for%20the%20IP%20dataset%20using%203%25%20training%20samples.png)
Figure 2. Classiﬁcation maps for the IP dataset using 3% training samples. (a) False-color image. (b) 
Ground-truth (GT). (c)–(h) The classiﬁcation maps with disparate algorithms. 
![UP](https://github.com/lironui/Double-Branch-Dual-Attention-Mechanism-Network/blob/master/figures/Figure%2010.%20Classi%EF%AC%81cation%20maps%20for%20the%20UP%20dataset%20using%200.5%25%20training%20samples.png)
Figure 3. Classiﬁcation maps for the UP dataset using 0.5% training samples. (a) False-color image. 
(b) Ground-truth (GT). (c)–(h) The classiﬁcation maps with disparate algorithms. 
![SV](https://github.com/lironui/Double-Branch-Dual-Attention-Mechanism-Network/blob/master/figures/Figure%2011.%20Classi%EF%AC%81cation%20maps%20for%20the%20SV%20dataset%20using%200.5%25%20training%20samples.png)
Figure 4. Classiﬁcation maps for the UP dataset using 0.5% training samples. (a) False-color image. 
(b) Ground-truth (GT). (c)–(h) The classiﬁcation maps with disparate algorithms. 
![BS](https://github.com/lironui/Double-Branch-Dual-Attention-Mechanism-Network/blob/master/figures/Figure%2012.%20Classi%EF%AC%81cation%20maps%20for%20the%20BS%20dataset%20using%201.2%25%20training%20samples.png)
Figure 5. Classiﬁcation maps for the BS dataset using 1.2% training samples. (a) False-color image. 
(b) Ground-truth (GT). (c)–(h) The classiﬁcation maps with disparate algorithms. 

