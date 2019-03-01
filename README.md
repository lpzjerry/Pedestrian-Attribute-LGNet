# Pedestrian-Attribute-LGNet
Source code for paper "Localization Guided Learning for Pedestrian Attribute Recognition"
Accepted by [British Machine Vision Conference (BMVC), 2018](http://bmvc2018.org/)

**[PDF]**(http://bmvc2018.org/contents/papers/0573.pdf)

Originally implemented on a customized Caffe with several layers:
- CalOverlap: Takes the IoU between two boxes as the affinity between proposals and attribute boxes. Ref: [This Paper](http://bmvc2018.org/contents/papers/0573.pdf)
- CamBox: Extract the "Class-Activation-Box" from the CAMs. Check [CAM (B.Zhou, 2016)](http://cnnlocalization.csail.mit.edu/) for more details.
- SigmoidCrossEntropyWeightLoss: Add a weight factor by the positive/negative ratio of each attribute. Check [DeepMar](https://ieeexplore.ieee.org/abstract/document/7486476) for details.

### Citation
```
@article{liu2018localization,
  title={Localization guided learning for pedestrian attribute recognition},
  author={Liu, Pengze and Liu, Xihui and Yan, Junjie and Shao, Jing},
  journal={arXiv preprint arXiv:1808.09102},
  year={2018}
}
```
