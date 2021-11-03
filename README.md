# CDEF
Most of the low light image data in the paper were selected from these four datasets, which are LIME, SIDD, HDR and ExDark, and the number of images is 10, 70, 292, 600 respectively. 

## Images displayed in paper

21 low light images displayed in the paper can be downloaded at this [https URL](https://cloud.189.cn/t/uIrMJv36RZVn) or [here](https://pan.baidu.com/s/1nNWskL1NKZSmK44XaSfqCg)(提取码：tqn3) (size = 42.41MB). 

## LIME dataset

10 images in LIME dataset can be downloaded at this [https URL](https://cloud.189.cn/t/AJRfYvUFBV3e) or [here](https://pan.baidu.com/s/1BOlXrvzTLDWhkLBbSiLmqQ)(提取码：pbql)   (size = 8.66MB).

## SIDD dataset

70 images in SIDD dataset can be downloaded at this [https URL](https://cloud.189.cn/t/IbmIZrzArAzm) or [here](https://pan.baidu.com/s/1lwZyfPGpumIJPkfPDCKxDQ)(提取码：rr71)(size = 8.12MB). 
This is the downsampling version of the original SIDD data. For reducing the calculation time, the statistical index experiment uses this.

Note:

1.70 images data can be found in SIDD-Small Dataset(Subset Download: [sRGB images only (~6 GB)](https://competitions.codalab.org/my/datasets/download/a26784fe-cf33-48c2-b61f-94b299dbc0f2) ). 'SIDD-Small Dataset' is a small version of SIDD Dataset. Almost all images with the 'L' suffix in the file name are selected as experimental images. For example: '0001_001_S6_00100_00060_3200_L'.

2.Please [click this address](https://www.eecs.yorku.ca/~kamel/sidd/dataset.php) to see more about the SIDD dataset.

## HDR dataset

292 pairs of images in HDR dataset can be downloaded at this [https URL](https://cloud.189.cn/t/yymaUrmuiMny) or [here](https://pan.baidu.com/s/1v8YoVVwJE5qLx_JldNAaXg)(提取码：q6ak) (size = 398.16MB).

The zip file contains two folders, the 'lowlight' folder and the 'Refimg' folder.

'lowlight' folder contains 292 images under low light.

'Refimg' folder contains 292 images under normal light.

Note: 

1.Please do not change the serial number of the images. They correspond to each other. e.g.  'HDRR(1).PNG' is the reference image under normal illumination of 'HDRL(1).PNG'.

2.The complete HDR data set includes 1811 images, from which we select 494 color images that meet the specific requirements.

Specific requirements include:

(1). The same size;

(2). The image under normal illumination is natural without color distortion;

(3). There is no shape distortion in the image under normal illumination.

3.Please [click this address](https://live.ece.utexas.edu/research/HDRDB/hdr_index.html) to see more about the HDR dataset.

## ExDark dataset

600 images in ExDark dataset can be downloaded at this [https URL](https://cloud.189.cn/t/jAbQveiqeEZb) or [here](https://pan.baidu.com/s/1ZbuaVg9J79hfqtjkKqVmog)(提取码：l5h1)(size = 110.70MB).

Note: 

1.The complete ExDark dataset includes 7363 images, from which we randomly selected 600 color images.

2.Please [click this address](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset) to see more about the ExDark dataset.


## citation

If you think the data set and code we collate are helpful for your research, please cite:

```

@article{CDEF,
  title={Low-light Image Enhancement Using Cell Vibration Model},
  author={Xiaozhou Lei and Minrui Fei and Wenju Zhou and Huiyu Zhou},
  booktitle={It has been submitted to the journal for review.},
  year={2021}
  month={11}
  day={2}
}


```

