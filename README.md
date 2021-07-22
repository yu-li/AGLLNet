<h2 align="center">AGLLNet: Attention Guided Low-light Image Enhancement (IJCV 2021) </h2>

This is the test code for  “Attention Guided Low-light Image Enhancement with a Large Scale Low-light Simulation Dataset” in IJCV 2021, by [Feifan Lv](https://lvfeifan.github.io/), [Yu Li](https://yu-li.github.io), and [Feng Lu](http://shi.buaa.edu.cn/lufeng/).

**<p align="center"><img src="http://yu-li.github.io/paper/lv_ijcv2021.jpg" height="240"/></p>**

**<p align="center">[Paper](https://link.springer.com/article/10.1007/s11263-021-01466-8) |	[ArXiv](https://arxiv.org/pdf/1908.00682.pdf) | [Project page (data)](http://www.phi-ai.org/project/AgLLNet/default.htm)</p>**


## Requirements ##

- [x] python 3.5  

- [x] Tensorflow 1.6.0

- [x] Keras 2.2.0

- [x] imageio

- [x] opencv

  

## Usage ##

#### Testing

You can put you image into the folder `input` and run

```shell
cd AGLLNet
python run_agllnet.py
```

The results will be stored in the folder `output`.



#### Training:

Training code will *NOT* be provided this time.




## Model

- [x] AgLLNet.h5  (This model is newly trained for general low light enhancement. It is not strictly the one used in our IJCV paper).

  
## Bibtex

If you use this code for your research, please consider star this repo and cite our paper.

 ```
 @article{lv2021attention,
  title={Attention guided low-light image enhancement with a large scale low-light simulation dataset},
  author={Lv, Feifan and Li, Yu and Lu, Feng},
  journal={International Journal of Computer Vision},
  volume={129},
  number={7},
  pages={2175--2193},
  year={2021}
}
 ```
 
 ## Related work: stable low light video enhancement
Learning Temporal Consistency for Low Light Video Enhancement from Single Images (CVPR2021)
[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Learning_Temporal_Consistency_for_Low_Light_Video_Enhancement_From_Single_CVPR_2021_paper.pdf) | [Code](https://github.com/zkawfanx/StableLLVE)
