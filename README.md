## PyTorch/Tensorflow Code for 'Deep k-Means: Re-Training and Parameter Sharing with Harder Cluster Assignments for Compressing Deep Convolutions'

### Introduction

This is the PyTorch/Tensorflow Implementation of our ICML 2018 paper ["Deep k-Means: Re-Training and Parameter Sharing with Harder Cluster Assignments for Compressing Deep Convolutions"]().

In our paper, We introduce a novel spectrally relaxed k -means regularization, that tends to approximately make hard assignments of convolutional layer weights to K learned cluster centers during re-training. Compression is then achieved through weight-sharing, by only recording K cluster centers and weight assignment indexes. 

Our proposed pipeline, termed Deep k -Means, has well-aligned goals between re-training and compression stages. We further propose an improved set of metrics to estimate energy consumption of CNN hardware implementations, whose estimation results are verified to be consistent with previously proposed energy estimation tool extrapolated from actual hardware measurements. We have evaluated Deep k -Means in compressing several CNN models in terms of both compression ratio and energy consumption reduction, observing promising results without incurring accuracy loss.

### Citation

If you find this code useful, please cite the following paper:

    @article{deepkmeans,
        title={Deep k-Means: Re-Training and Parameter Sharing with Harder Cluster Assignments for Compressing Deep Convolutions},
        author={Junru Wu, Yue Wang, Zhenyu Wu, Zhangyang Wang, Ashok Veeraraghavan, Yingyan Lin},
        journal={ICML},
        year={2018}
    }
    
### To do items

#### PyTorch Model

- [ ] Wide ResNet
- [ ] LeNet Caffe
- [ ] FreshNet
- [ ] TT-conv

#### Tensorflow Model

- [ ] GoogleNet
- [ ] AlexNet

#### Code

- [ ] Support both PyTorch and Tensorflow for all models (GoogleNet/ AlexNet/ Wide ResNet/ FreshNet/ TT-Conv).

### Dependencies

* Python 3.5
* [PyTorch 0.3.1](https://pytorch.org/previous-versions/)
* [libKMCUDA 6.2.1](https://github.com/src-d/kmcuda)
* sklearn 0.19.1
* MATLAB R2017b
* [MATLAB Engine](https://www.mathworks.com/help/matlab/matlab_external/install-the-matlab-engine-for-python.html)


### Testing Deep k-Means
