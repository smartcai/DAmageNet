# Authors
* Sizhe Chen, csz729020210@sjtu.edu.cn
* Xiaolin Huang*, xiaolinhuang@sjtu.edu.cn
* Zhengbao He, lstefanie@sjtu.edu.cn
* Chengjin Sun, sunchengjin@sjtu.edu.cn
* Institute of Image Processing and Pattern Recognition in Shanghai Jiao Tong University

# Description
* Details of DAmageNet can be viewed in paper [DAmageNet: A Universal Adversarial Dataset](https://arxiv.org/abs/1912.07160)
* DAmageNet is a massive dataset containing universal adversarial samples generated from ImageNet.
* DAmageNet contains 96020 224*224 images, whose original images have been centrally cropped and resized.
* DAmageNet images have an average root mean square deviation of around 4.2 from original samples.
* DAmageNet can fool pretrained models in ImageNet to have error rate up to 90%.

# Data
* Each folder in ./DAmageNet contains samples in one class, which are distributed in 10 .tar files.
* The class labels are corresponding to ImageNet in terms of numerical order.
* The name of image in DAmageNet is the same as that of the original clean image in ImageNet.
* Comparison between ImageNet and DAmageNet samples can be viewed in ./demo
* [Download](http://www.pami.sjtu.edu.cn/Show/56/122)

# Demo
<img src="https://github.com/AllenChen1998/DAmageNet/blob/master/intro.png" height="280"><img src="https://github.com/AllenChen1998/DAmageNet/blob/master/results.png" height="280"><img src="https://github.com/AllenChen1998/DAmageNet/blob/master/samples.png" height="280">
