### ContourNet
Richer Convolutional Features for Contour Detection on PASCAL VOC 2012 Dataset.

### Introduction
My ContourNet(CNet) can be used to detection the object contour on PASCAL VOC 2012 Dataset.
CNet refer <a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Liu_Richer_Convolutional_Features_CVPR_2017_paper.pdf">RCF</a>,
<a href="http://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_Learning_a_Discriminative_CVPR_2018_paper.pdf">DFN</a> and <a href="http://openaccess.thecvf.com/content_cvpr_2016/papers/Yang_Object_Contour_Detection_CVPR_2016_paper.pdf">CEDN</a>.

### Dataset and Preprocessed
In <a href="http://openaccess.thecvf.com/content_cvpr_2016/papers/Yang_Object_Contour_Detection_CVPR_2016_paper.pdf">CEDN</a>, they proposed the method of preprocessing data. Actually, they have provided the <a href="https://github.com/jimeiyang/objectContourDetector/blob/master/data/PASCAL/get_pascal_training_data.sh">preprocessed-data</a>.

### My Results
| Method |Original Motivation|ODS F-score|OIS F-score|AP|
|:---|:---|:---|:---|:---|
| CNet(Ours) |Contour Detection|0.494|0.509|0.373|
| CEDN |Contour Detection|0.486|0.500|0.354|
| RCF |Edge Detection|0.459|0.475|0.333|
| HED |Edge Detection|0.441|0.454|0.311|

note: The same environment means the same data augmentation, the same framework, the same time seed and so on.

### Environment
pytorch-1.0.0, numpy, PIL

### Thanks
Thanks to <a href="https://github.com/meteorshowers">XuanYi Li</a>, <a href="https://github.com/shenwei1231">Wei Shen</a>.

### Contact
zhangchbin AT gmail.com
