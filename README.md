# Spatial Transformer Network

The Spatial Transformer Network [1] allows the spatial manipulation of data within the network.

<div align="center">
  <img width="600px" src="http://i.imgur.com/ExGDVul.png"><br><br>
</div>

A Spatial Transformer Network implemented in Tensorflow 1.3.0 and based on [2].

#### Architecture
<div align="center">
  <img src="http://i.imgur.com/gfqLV3f.png"><br><br>
</div> 

#### Experiments

We created RTS MNIST dataset by applying rotation, translation and scaling transformations on the original MNIST data. 
The dataset can be found <a href="https://drive.google.com/open?id=0B8BI4Wvs0CZpVkdvNnV3QnBmWTA">here</a>

All experiments were run in Tensorflow 1.3.0 on a GPU machine. Extensive results included the generated samples can be found <a href="https://drive.google.com/drive/folders/0B8BI4Wvs0CZpVnJXb1pVS2dYNEE?usp=sharing">here</a>.
We have also created videos for the samples generated by each model.

### References

[1] Jaderberg, Max, et al. "Spatial Transformer Networks." arXiv preprint arXiv:1506.02025 (2015)

[2] https://github.com/daviddao/spatial-transformer-tensorflow
