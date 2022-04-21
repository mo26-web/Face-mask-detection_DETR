# Face-mask-detection_DETR
This is a face mask detection project implemented with the Pytorch. We use  End-to-End Object Detection with Transformers model (DETR) and Face Mask Detection dataset available on kaggle.

**DE⫶TR**: End-to-End Object Detection with Transformers
========

PyTorch training code and pretrained models for **DETR** (**DE**tection **TR**ansformer).
We replace the full complex hand-crafted object detection pipeline with a Transformer, and match Faster R-CNN with a ResNet-50, obtaining **42 AP** on COCO using half the computation power (FLOPs) and the same number of parameters. Inference in 50 lines of PyTorch.

![DETR](https://github.com/facebookresearch/detr/raw/main/.github/DETR.png)

**What it is**. Unlike traditional computer vision techniques, DETR approaches object detection as a direct set prediction problem. It consists of a set-based global loss, which forces unique predictions via bipartite matching, and a Transformer encoder-decoder architecture. 
Given a fixed small set of learned object queries, DETR reasons about the relations of the objects and the global image context to directly output the final set of predictions in parallel. Due to this parallel nature, DETR is very fast and efficient.

# Face mask dataset

Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization. With this dataset, it is possible to create a model to detect people wearing masks, not wearing them, or wearing masks improperly.
This dataset contains 853 images belonging to the 3 classes, as well as their bounding boxes in the PASCAL VOC format.
The classes are:

With mask;
Without mask;
Mask worn incorrectly.

Available at: https://www.kaggle.com/andrewmvd/datasets

# Split dataset
<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/labeld.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/labeld.png" align="center"></a>
</p>
<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/labeld2.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/labeld2.png" align="center"></a>
</p>

# Results

<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/22.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/22.png" align="center"></a>
</p>

<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/26.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/26.png" align="center"></a>
</p>

<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/30.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/30.png" align="center"></a>
</p>

<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/8.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/8.png" align="center"></a>
</p>

<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/14.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/14.png" align="center"></a>
</p>

<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/7.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/7.png" align="center"></a>
</p>

<p align="center">
<a href="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/17.png"><img src="https://github.com/mo26-web/Face-mask-detection_DETR/blob/main/images/17.png" align="center"></a>
</p>






