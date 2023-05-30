# Centerfusion
Sorry, the already unpacked dataset doesn't seem to upload, you can download it yourself from the official website. Then decompress it and convert it.  
It is recommended that the server should have 128GB of RAM to run all datasets, otherwise run mini datasets
This is a rewrite based on the original author's code, patching some bugs, you can do dual card training directly. Or modify the gpu parameter in train.sh or test, if you modify please remember to modify the parameter in the first line. 
If you want to train the whole data, please make sure you have 120GB of running memory. if not you can try the mini data set.
Thanks to the open source people on the web here are the detailed steps:CenterFusion project super detailed environment build steps and visual operation：https://blog.csdn.net/ssj925319/article/details/124294911


The environment is
```
conda install pytorch==1.7.1 torchvision==0.8.2 torchaudio==0.7.2 cudatoolkit=11.0 -c pytorch
pip install -r requirements.txt
```

Then you can train with dual cards(GPUS)


Here is the citation:https://github.com/mrnabati/CenterFusion

@inproceedings{zhou2019objects,
title={Objects as Points},
author={Zhou, Xingyi and Wang, Dequan and Kr{\"a}henb{\"u}hl, Philipp},
booktitle={arXiv preprint arXiv:1904.07850},
year={2019}
}

@article{zhou2020tracking,
title={Tracking Objects as Points},
author={Zhou, Xingyi and Koltun, Vladlen and Kr{\"a}henb{\"u}hl, Philipp},
journal={ECCV},
year={2020}
}

@inproceedings{nuscenes2019,
title={{nuScenes}: A multimodal dataset for autonomous driving},
author={Holger Caesar and Varun Bankiti and Alex H. Lang and Sourabh Vora and Venice Erin Liong and Qiang Xu and Anush Krishnan and Yu Pan and Giancarlo Baldan and Oscar Beijbom},
booktitle={CVPR},
year={2020}
}





