# DefRec
 
 ### Introduction
Code to implement DefRec on single dataset.

[[Paper]](https://arxiv.org/pdf/2003.12641.pdf)

### Instructions

Create Virtual Environment
```bash
conda create -n myenv python=3.7.10
conda activate myenv
```

Clone repo and install it
```bash
git clone https://github.com/mohammedshariqnawaz/DefRec_3D.git
cd DefRec_3D
pip install -e .
```

Download data:
```bash
cd ./PointDA/data
python download.py
```

Train the model:
```bash
cd ./PointDA
python trainer.py
```



### Citation
Please cite this paper if you want to use it in your work,
```
@inproceedings{achituve2021self,
  title={Self-Supervised Learning for Domain Adaptation on Point Clouds},
  author={Achituve, Idan and Maron, Haggai and Chechik, Gal},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={123--133},
  year={2021}
}
```

 
### Acknowledgement
Some of the code in this repoistory was taken (and modified according to needs) from the follwing sources:
[[PointNet]](https://github.com/charlesq34/pointnet), [[PointNet++]](https://github.com/charlesq34/pointnet2), [[DGCNN]](https://github.com/WangYueFt/dgcnn), [[PointDAN]](https://github.com/canqin001/PointDAN), [[Reconstructing_space]](http://papers.nips.cc/paper/9455-self-supervised-deep-learning-on-point-clouds-by-reconstructing-space), [[Mixup]](https://github.com/facebookresearch/mixup-cifar10)


