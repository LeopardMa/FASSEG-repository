Welcome to the webpage of the **FAce Semantic SEGmentation** (_FASSEG_) dataset.

The FASSEG dataset is made available here in two versions:

- **V1** contains 70 labeled faces and the original RGB images. **This is exactly the same dataset we used in our paper** [1]. Faces are mainly taken from the MIT-CBCL[2] and FEI[3] datasets. Images are organized in two folders - train and test -  matching the division we adopted in the paper.

- **V2** is a *"high-precision V1"*. It contains the same images as the V1 but it's much more precise in the segmentations (see images below). We also introduced a different convention for the "nose" class, which is extended up to the level of the eyes.  

<BR> 
<p> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <img src="https://raw.githubusercontent.com/massimomauro/FASSEG-dataset/master/other/V1V2_diff.png" alt="V1_V2_differences" width="600"> </p>

Our advice is: if you need to compare with our results, choose V1. If you need a dataset to build your models, choose V2.

In any case, if you use our datasets, please cite our work [1].

[1] *Massimo Mauro*, *Khalil Khan*, *Riccardo Leonardi*, **"Multi-class semantic segmentation of faces"**, International Conference on Image Processing (ICIP), 2015

[2] *MIT Center for Biological and Computational Learning (CBCL)*, **MIT-CBCL database**, [http://cbcl.mit.edu/software-datasets/FaceData2.html](http://cbcl.mit.edu/software-datasets/FaceData2.html)

[3] *Centro Universitario da FEI*, **FEI database**,
[http://www.fei.edu.br/~cet/facedatabase.html](http://www.fei.edu.br/~cet/facedatabase.html)