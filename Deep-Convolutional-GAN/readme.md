
# Deep Convolutional GAN in TensorFlow and PyTorch
**This repository contains code for [Deep Convolutional GAN in TensorFlow and PyTorch](https://learnopencv.com/deep-convolutional-gan-in-pytorch-and-tensorflow/) blogpost**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/hmlrgfz4wvpm6wf/AAChCpEYJK74EQxjs8PTHyIta?dl=1)


## Package Dependencies

The repository also trains the Deep Convolutional GAN in both Pytorch and Tensorflow on [Anime-Faces dataset](https://github.com/bchao1/Anime-Face-Dataset). It is tested with the following CUDA versions.

- `Cuda-11.1`
- `Cudnn-8.0`

The Pytorch and Tensorflow scripts require [numpy](https://numpy.org/), [tensorflow](https://www.tensorflow.org/install), [torch](https://pypi.org/project/torch/).  To get the versions of these packages you need for the program, use pip: (Make sure pip is upgraded. ` python3 -m pip install -U pip`)
```
pip3 install -r requirements.txt 
```

## Directory Structure


```
├── PyTorch
│   ├── DCGAN_Anime_Pytorch.ipynb
│   └── dcgan_anime_pytorch.py
└── TensorFlow
    ├── DCGAN_Anime_Tensorflow.ipynb
    └── dcgan_anime_tesnorflow.py
```



## Instructions

### PyTorch

To train the Deep Convolutional GAN with Pytorch, please go into the `Pytorch` folder and execute the Jupyter Notebook.

### TensorFlow

To train the Deep Convolutional GAN with TensorFlow, please go into the `Tensorflow` folder and execute the Jupyter Notebook.


# AI Courses by OpenCV

Want to become an expert in AI? [AI Courses by OpenCV](https://opencv.org/courses/) is a great place to start.

[![img](https://learnopencv.com/wp-content/uploads/2023/01/AI-Courses-By-OpenCV-Github.png)](https://opencv.org/courses/)
