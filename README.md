# DLOSC
This project includes two datasets for Deformable Linear Objects(DLOs) segmentation task and DLO crossings classification task, named [DLOSS](#dataset-for-dlos-segementationdloss--download) and [DLOCC](#dataset-for-dlo-crossings-classificationdlocc--download) respectively.
<br><br><br>
## Publishment: Untangling Multiple Deformable Linear Objects in Unknown Quantities With Complex Backgrounds | [IEEE Xplore](https://ieeexplore.ieee.org/document/10026277)
[![Untangling of Multiple Deformable Linear Objects in Unknown Quantity with Complex Backgrounds](https://res.cloudinary.com/marcomontalbano/image/upload/v1667738600/video_to_markdown/images/youtube--wReD4qDMN4k-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/wReD4qDMN4k "Untangling of Multiple Deformable Linear Objects in Unknown Quantity with Complex Backgrounds")
<br><br><br>
## Dataset for DLO Crossings Classification(DLOCC) | [Download](https://drive.google.com/drive/folders/1vY-Z_7Dg98PyUO8UzyBso9N5jDXJDqa9?usp=sharing)
Dataset DLOCC aims to be used in the DLO crossings classification tasks. Only crossings consisting of two DLO segments at one point are considered here. 

As shown in the following figure, Arrow 'D' denotes the direction in which the segment is traced. Crossings were cropped by a square boundary, the rotation angle of which depends on the direction of arrow 'D'. 'D' always appears at the midpoint of the boundary's side. 

![Fig.1](./figures/Crop_method.png)

After rotation, the direction 'D' in the cropped crossing region is upwards. The DLO segment entered from the midpoint of the bottom boundary is regarded as the target DLO segment. Examples here in the above figure map to (a) and (e) below:

![Fig.1](./figures/Cropped_crossing_region.png)

Cropped crossing regions were classified into two categories: UPPER and LOWER. The category represents the anteroposterior position of the two segments in the crossing. Four different backgrounds were used during data collection. 

### Information
- Image size: 50x50(pixels);
- File format: .png(zip);
- Dataset scales: 1883 UPPER images + 1883 LOWER images.

<br><br>
## Dataset for DLOs Segementation(DLOSS) | [Download](https://drive.google.com/drive/folders/1Y7g3vsS8e2MvCvQczXEkQI6sUg8tD0Ok?usp=sharing)
Dataset DLOSS aims to be used in single-DLO or multi-DLOs segmentation tasks. 

As shown in the first collum of the following figure, DLO(s) were placed on four different backgrounds with some distracting objects. The second collum shows the DLO contours. The overlap parts in the crossing areas are marked as blue circles. The third collum further indicates the gradient map of the contours. In the gradient map, the DLO segments are depicted by colors of varying shades from one endpoint of the DLO to the other. 

![Fig.1](./figures/SegmentationDataSamples.png)

### Information
- Image size: 960x540(pixels);
- File format: .bmp(zip/rar);
- Dataset scales: 2000 single DLO + 1500 multi DLOs.

<br><br>
## Citation
Plain Text
```
X. Huang, D. Chen, Y. Guo, X. Jiang and Y. Liu, "Untangling Multiple Deformable Linear Objects in Unknown Quantities With Complex Backgrounds," in IEEE Transactions on Automation Science and Engineering, doi: 10.1109/TASE.2023.3233949.
```
BibTex
```latex
@ARTICLE{10026277,
  author={Huang, Xuzhao and Chen, Dayuan and Guo, Yuhao and Jiang, Xin and Liu, Yunhui},
  journal={IEEE Transactions on Automation Science and Engineering}, 
  title={Untangling Multiple Deformable Linear Objects in Unknown Quantities With Complex Backgrounds}, 
  year={2023},
  volume={},
  number={},
  pages={1-13},
  doi={10.1109/TASE.2023.3233949}}
```
Plain Text
```
Y. Song, K. Yang, X. Jiang and Y. Liu, "Vision Based Topological State Recognition for Deformable Linear Object Untangling Conducted in Unknown Background," 2019 IEEE International Conference on Robotics and Biomimetics (ROBIO), Dali, China, 2019, pp. 790-795, doi: 10.1109/ROBIO49542.2019.8961652.
```
BibTex
```latex@INPROCEEDINGS{8961652,
  author={Song, Yu and Yang, Kang and Jiang, Xin and Liu, Yunhui},
  booktitle={2019 IEEE International Conference on Robotics and Biomimetics (ROBIO)}, 
  title={Vision Based Topological State Recognition for Deformable Linear Object Untangling Conducted in Unknown Background}, 
  year={2019},
  volume={},
  number={},
  pages={790-795},
  doi={10.1109/ROBIO49542.2019.8961652}}

```
<br><br>
