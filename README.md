# Panoptic-Segmentation

What is Panoptic Segmentation?

<img src="https://user-images.githubusercontent.com/25415975/145647434-c70015c8-51e8-4b0f-a730-0b25ea8420dd.png" width=60% height=60%>

Fig 1: Instance Segmentation
Identification of "thing", where a "thing" is a countable object such as people, car, etc

Fig 2: Semantic Segmentation
Identification of "stuff", where stuff is an amorphous region of similar texture such as road, sky, etc, thus it’s a category without instance-level annotation

Fig 3: Panoptic Segmentation
Combination of both, the label encoding of pixels in panoptic segmentation involves assigning each pixel of an image two labels – one for the semantic label, and the other for instance id 



**Implementation of Panoptic Segmentation on COCO Dataset using Detectron2 open-source package by Facebook AI Research team**

Panoptic Segmentation Architecture

<img src="https://user-images.githubusercontent.com/25415975/145644850-633ea483-f0df-4c90-83e1-be177baedcc4.png" width=50% height=50%>


Final Results!

Below image shows how panoptic segmentation identifies both instances and semantics using a single unified network

<img src="https://user-images.githubusercontent.com/25415975/145644917-ebea0092-0e3c-4c00-b54e-b8c65ccd601a.png" width=50% height=50%>

Link: https://github.com/facebookresearch/detectron2
