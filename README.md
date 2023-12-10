# TransRUPNet for Improved Out-of-Distribution Generalization in Polyp Segmentation

Out-of-distribution (OOD) generalization is a critical challenge in deep learning. It is specifically important when the test samples are drawn from a distribution different from the training data. We develop a novel real-time deep learning based architecture, TransRUPNet that is based on a Transformer and residual upsampling network for colorectal polyp segmentation to improve OOD generalization. The proposed architecture, TransRUPNet, is an encoder-decoder network that consists of three encoder blocks, three decoder blocks, and some additional upsampling blocks at the end of the network. With the image size of 256×256, the proposed method achieves an excellent real-time operation speed of 47.07 frames per second with an average mean dice coefficient score of 0.7786 and mean Intersection over Union of 0.7210 on the out-of-distribution polyp datasets. The results on the publicly available PolypGen dataset (OOD dataset in our case) suggest that TransRUPNet can give real-time feedback while retaining high accuracy for in-distribution datasets. Furthermore, we demonstrate the generalizability of the proposed method by showing that it significantly improves performance on OOD datasets compared to the existing methods.

## Architecture
<p align="center">
<img src="img/TransRUPNet.jpg">
</p>

## Datasets:
The following datasets are used in this experiment:
<ol>
  <li>MICCAI 2015 Segmentation challenge(CVC-ClinicDB for training and ETIS-Larib for Testing)</li>
  <li>[CVC-ClinicDB] (https://www.kaggle.com/datasets/balraj98/cvcclinicdb)</li>
  <li>[Lesion Boundary segmentation challenge] (https://challenge.isic-archive.com/data/)/li>
  <li> [2018 Data Science Bowl challenge] (https://bbbc.broadinstitute.org/BBBC038/)</li>
 </ol>


 <p align="center">
<img src="img/blocks.jpg">
</p>


## Results

 <p align="center">
<img src="img/results.jpg">
</p>

 <p align="center">
<img src="img/Quantitative.png">
</p>



## Citation
Please cite our paper if you find the work useful: 
<pre>
@article{jha2023transrupnet,
  title={TransRUPNet for Improved Out-of-Distribution Generalization in Polyp Segmentation},
  author={Jha, Debesh and Tomar, Nikhil Kumar and Bagci, Ulas},
  journal={arXiv preprint arXiv:2306.02176},
  year={2023}
}
</pre>

## Contact
please contact debesh.jha@northwestern.edu for any further questions. 


