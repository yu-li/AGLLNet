<h2 align="center">AGLLNet: Attention Guided Low-light Image Enhancement (IJCV 2021) </h2>

This is the test code for  “Attention Guided Low-light Image Enhancement with a Large Scale Low-light Simulation Dataset” in IJCV 2021, by [Feifan Lv](https://lvfeifan.github.io/), [Yu Li](yu-li.github.io), and  [Feng Lu](http://shi.buaa.edu.cn/lufeng/).


**<p align="center">[Paper](https://link.springer.com/article/10.1007/s11263-021-01466-8) |	[ArXiv](https://arxiv.org/pdf/1908.00682.pdf) | [Project page (data)](http://www.phi-ai.org/project/AgLLNet/default.htm)</p>**


## Requirements ##

- [x] python 3  
- [x] Tensorflow 1.6.0
- [x] Keras 2.2.0
- [x] Opencv-python 3.4.2

## Usage ##

#### Testing

To quickly test your own low-light images with our model, you can just run through

```shell
cd main
python test.py -i <input folder> -r <output folder> -m <model name>
```

By default, the code takes the data in the "../input/" folder, loads the "Syn_img_lowlight_withnoise.h5" model and saves results in the "../result/" folder.  Please read the code to see other parameter settings. 

#### Training:

Training code will NOT be provided this time.


## Model

- [x] TBD.h5  (This model is trained using synthetic lowlight images based on Poisson noise model. It is using for enhancement and denoising simultaneously.)

  
## Bibtex

If you use this code for your research, please cite our paper.

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


