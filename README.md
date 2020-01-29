# Leaderboard for Domain Adaptation for Semantic Segmentation


Synthetic to real domain adaptation is a standard setup used in state-of-the-art methods recently. Below two leaderboards for GTA-V to Cityscapes and SYNTHIA to Cityscapes are shown. Each paper is represented with its nickname, venue and year of publication. The approchares used in different papers are abbrevated as "ST" for Self-training or self-supervised learning and "Adv" for adversarial learning respectively. The papers are in descending order with respect to mean Intersection over Union (mean IoU). 


## GTA-V to Cityscapes Adaptation
### ResNet
| Methods        | Venue/Year | Approach        | mean IoU | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Terrain | Sky | Person | Rider | Car | Truck | Bus | Train | Motorcycle | Bicycle |
| -------------- | ----- |:---------------:| -------- | ----- | -------- | -------- | ---- | ----- | ---- | -------- | ------- | ---------- | ------- | --- | ------ | ----- | --- | ----- | --- | ----- | ---------- | ------- |
| [MLSL (Ours)](https://arxiv.org/abs/1909.13776) |WACV-2020|ST| 49.0 | 89.0 | 45.2 | 78.2 | 22.9 | 27.3 | 37.4 | 46.1 | 43.8 | 82.9 | 18.6 | 61.2 | 60.4 | 26.7 | 85.4 | 35.9 | 44.9 | 36.4 | 37.2 | 49.3 |
| [BDL](https://arxiv.org/abs/1904.10620) |CVPR-2019|Adv+ST| 48.5 | 91.0 | 44.7 | 84.2 | 34.6 | 27.6 | 30.2 | 36.0 | 36.0 | 85.0 | 43.6 | 83.0 | 58.6 | 31.6 | 83.3 | 35.3 | 49.7 | 3.3 | 28.8 | 35.6 |
| [CRST](https://arxiv.org/abs/1908.09822) |ICCV-2019|ST| 46.8 | 84.5 | 47.7 | 74.1 | 27.9 | 22.1 | 43.8 | 46.5 | 37.8 | 83.7 | 22.7 | 56.1 | 56.8 | 26.8 | 81.7 | 22.5 | 46.2 | 27.5 | 32.3 | 47.9 |
| [DPR](https://arxiv.org/pdf/1901.05427.pdf) |ICCV-2019|Adv| 46.5 | 92.3 | 51.9 | 82.1 | 29.2 | 25.1 | 24.5 | 33.8 | 33.0 | 82.4 | 32.8 | 82.2 | 58.6 | 27.2 | 84.3 | 33.4 | 46.3 | 2.2 | 29.5 | 32.3 |
| [MaxSquare](https://arxiv.org/abs/1909.13589) |ICCV-2019|Adv+ST| 46.4 | 89.4 |43.0 |82.1 |30.5 |21.3 |30.3 |34.7 |24.0 |85.3 |39.4 |78.2 |63.0 |22.9 |84.6 |36.4 |43.0 |5.5 |34.7 |33.5 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV-2018|ST| 46.2 | 88.0 | 56.2 | 77.0 | 27.4 | 22.4 | 40.7 | 47.3 | 40.9 | 82.4 | 21.6 | 60.3 | 50.2 | 20.4 | 83.8 | 35.0 | 51.0 | 15.2 | 20.6 | 37.0 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR-2019|Adv| 45.4 | 91.5 | 47.5 | 82.5 | 31.3 | 25.6 | 33.0 | 33.7 | 25.8 | 82.7 | 28.8 | 82.7 | 62.4 | 30.8 | 85.2 | 27.7 | 34.5 | 6.4 | 25.2 | 24.4 |
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR-2019|Adv+ST|  45.5| 89.4| 33.1| 81.0| 26.6| 26.8| 27.2| 33.5| 24.7| 83.9| 36.7| 78.8| 58.7| 30.5| 84.8| 38.5| 44.5| 1.7| 31.6| 32.4|
| [CLAN](https://arxiv.org/abs/1809.09478) |CVPR-2019|Adv| 43.2 | 87.0 | 27.1 | 79.6 | 27.3 | 23.3 | 28.3 | 35.5 | 24.2 | 83.6 | 27.4 | 74.2 | 58.6 | 28.0 | 76.2 | 33.1 | 36.7 | 6.7 | 31.9 | 31.4 |
| [Saleh etal](https://arxiv.org/abs/1807.06132) |ECCV-2018|Adv| 42.5 | 79.8 | 29.3 | 77.8 | 24.2 | 21.6 | 6.9 | 23.5 | 44.2 | 80.5 | 38.0 | 76.2 | 52.7 | 22.2 | 83.0 | 32.3 | 41.3 | 27.0 | 19.3 | 27.7 |
| [AdaptNet](https://arxiv.org/abs/1802.10349) |CVPR-2018|Adv| 42.4 | 86.5 | 36.0 | 79.9 | 23.4 | 23.3 | 23.9 | 35.2 | 14.8 | 83.4 | 33.3 | 75.6 | 58.5 | 27.6 | 73.7 | 32.5 | 35.4 | 3.9 | 30.1 | 28.1 |
| [DLOW](https://arxiv.org/abs/1812.05418) |CVPR-2019|Adv| 42.3 | 87.1 | 33.5 | 80.5 | 24.5 | 13.2 | 29.8 | 29.5 | 26.6 | 82.6 | 26.7 | 81.8 | 55.9 | 25.3 | 78.0 | 33.5 | 38.7 | 0.0 | 22.9 | 34.5 |

### VGG-16
| Methods        | Venue/Year | Approach        | mean IoU | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Terrain | Sky | Person | Rider | Car | Truck | Bus | Train | Motorcycle | Bicycle |
| -------------- | ----- |:---------------:| -------- | ----- | -------- | -------- | ---- | ----- | ---- | -------- | ------- | ---------- | ------- | --- | ------ | ----- | --- | ----- | --- | ----- | ---------- | ------- |
| [MLSL (Ours)](https://arxiv.org/abs/1909.13776) |WACV-2020|ST| 49.0 | 89.0 | 45.2 | 78.2 | 22.9 | 27.3 | 37.4 | 46.1 | 43.8 | 82.9 | 18.6 | 61.2 | 60.4 | 26.7 | 85.4 | 35.9 | 44.9 | 36.4 | 37.2 | 49.3 |
| [BDL](https://arxiv.org/abs/1904.10620) |CVPR-2019|Adv+ST| 41.3| 89.2| 40.9| 81.2| 29.1| 19.2| 14.2| 29.0| 19.6| 83.7| 35.9| 80.7| 54.7| 23.3| 82.7| 25.8| 28.0| 2.3| 25.7| 19.9|
| [DPR](https://arxiv.org/pdf/1901.05427.pdf) |ICCV-2019|Adv| 37.5| 87.3| 35.7| 79.5| 32.0| 14.5| 21.5| 24.8| 13.7| 80.4| 32.0| 70.5| 50.5| 16.9| 81.0| 20.8| 28.1| 4.1| 15.5| 4.1|
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV-2018|ST| 36.1 | 90.4 |50.8 |72.0 |18.3 |9.5 |27.2 |28.6 |14.1 |82.4 |25.1 |70.8 |42.6 |14.5 |76.9 |5.9 |12.5 |1.2 |14.0 |28.6|
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR-2019|Adv| 45.4 | 91.5 | 47.5 | 82.5 | 31.3 | 25.6 | 33.0 | 33.7 | 25.8 | 82.7 | 28.8 | 82.7 | 62.4 | 30.8 | 85.2 | 27.7 | 34.5 | 6.4 | 25.2 | 24.4 |
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR-2019|Adv| 36.1| 86.9| 28.7| 78.7| 28.5| 25.2| 17.1| 20.3| 10.9| 80.0| 26.4| 70.2| 47.1| 8.4| 81.5| 26.0| 17.2| 18.9| 11.7| 1.6|
| [CLAN](https://arxiv.org/abs/1809.09478) |CVPR-2019|Adv|36.6| 88.0| 30.6| 79.2| 23.4| 20.5| 26.1| 23.0| 14.8| 81.6| 34.5| 72.0| 45.8| 7.9| 80.5| 26.6| 29.9| 0.0| 10.7| 0.0| 
| [Saleh etal](https://arxiv.org/abs/1807.06132) |ECCV-2018|Adv| 42.5 | 79.8 | 29.3 | 77.8 | 24.2 | 21.6 | 6.9 | 23.5 | 44.2 | 80.5 | 38.0 | 76.2 | 52.7 | 22.2 | 83.0 | 32.3 | 41.3 | 27.0 | 19.3 | 27.7 |
| [AdaptNet](https://arxiv.org/abs/1802.10349) |CVPR-2018|Adv(sigle level)|35.0| 87.3| 29.8| 78.6| 21.1| 18.2| 22.5| 21.5| 11.0| 79.7| 29.6| 71.3| 46.8| 6.5| 80.1| 23.0| 26.9| 0.0| 10.6| 0.3| 




## SYNTHIA to Cityscapes Adaptation
### ResNet
| Methods        | Venue/Year | Approach        | mean IoU | mean IoU* | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Sky | Person | Rider | Car | Bus | Motorcycle | Bicycle |
| -------------- | ---------- |:---------------:| -------- | --------- | ----- | -------- | -------- | ---- | ----- | ---- | ------- | ------ | ---------- | --- | ------ | ----- | --- | --- | ---------- | ------- |
| [BDL](https://arxiv.org/abs/1904.10620) |CVPR-2019|Adv+ST| - |51.4| 86.0| 46.7| 80.3| -| -| -| 14.1| 11.6| 79.2| 81.3| 54.1| 27.9| 73.7| 42.2| 25.7| 45.3| 
| [MLSL (Ours)](https://arxiv.org/abs/1909.13776) |WACV-2020|ST| 45.2 | 51.0 | 59.2 | 30.2 | 68.5 | 22.9 | 1.0 | 36.2 | 32.7 | 28.3 | 86.2 | 75.4 | 68.6 | 27.7 | 82.7 | 26.3 | 24.3 | 52.7 |
| [CRST](https://arxiv.org/abs/1908.09822) |ICCV-2019|ST| 43.8 | 50.1 | 67.7 | 32.2 | 73.9 | 10.7 | 1.6 | 37.4 | 22.2 | 31.2 | 80.8 | 80.5 | 60.8 | 29.1 | 82.8 | 25.0 | 19.4 | 45.3 |
| [DADA](https://arxiv.org/abs/1904.01886) |ICCV-2019|Adv| 42.6 | 49.8 | 89.2 | 44.8 | 81.4 |6.8 |0.3 |26.2 |8.6 |11.1 |81.8 |84.0 |54.7 |19.3 |79.7 |40.7 |14.0 |38.8 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV-2018|ST| 42.5 | 48.4 | 53.6 | 23.7 | 75.0 | 12.5 | 0.3 | 36.4 | 23.5 | 26.3 | 84.8 | 74.7 | 67.2 | 17.5 | 84.5 | 28.4 | 15.2 | 55.8 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR-2019|Adv| 41.5 | 48.7 | 91.7 | 53.5 | 77.1 | 2.5 | 0.2 | 27.1 | 6.2 | 7.6 | 78.4 | 81.2 | 55.8 | 19.2 | 82.3 | 30.3 | 17.1 | 34.3 |
| [MaxSquare](https://arxiv.org/abs/1909.13589) |ICCV-2019|Adv+ST| 41.4 | 48.2 | 82.9 | 40.7 | 80.3 | 10.2 | 0.8 | 25.8 | 12.8 | 18.2 | 82.5 | 82.2 | 53.1 | 18.0 | 79.0 | 31.4 | 10.4 | 35.6|
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR-2019|Adv+ST| 41.2 | 48.0 | 85.6 | 42.2 | 79.7 | 8.7 | 0.4 | 25.9 | 5.4 | 8.1 | 80.4 | 84.1 | 57.9 | 23.8 | 73.3 | 36.4 | 14.2 | 33.0 |
| [CLAN](https://arxiv.org/abs/1809.09478) |CVPR-2019|Adv| - |47.8| 81.3| 37.0| 80.1| - | - | - | 16.1| 13.7| 78.2| 81.5| 53.4| 21.2| 73.0| 32.9| 22.6| 30.7| 
| [AdaptNet](https://arxiv.org/abs/1802.10349) |CVPR-2018|Adv| - | 46.7 | 84.3 | 42.7 | 77.5 | -|-|-|4.7 | 7.0 | 77.9 | 82.5 | 54.3 | 21.0 | 72.3 | 32.2 | 18.9 | 32.3 |
| [DPR](https://arxiv.org/pdf/1901.05427.pdf) |ICCV-2019|Adv| 40.0 | 46.5 | 82.4 | 38.0 | 78.6 | 8.7 | 0.6 | 26.0 | 3.9 | 11.1 | 75.5 | 84.6 | 53.5 | 21.6 | 71.4 | 32.6 | 19.3 | 31.7 |

### VGG-16

| Methods        | Venue/Year | Approach        | mean IoU | mean IoU* | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Sky | Person | Rider | Car | Bus | Motorcycle | Bicycle |
| -------------- | ---------- |:---------------:| -------- | --------- | ----- | -------- | -------- | ---- | ----- | ---- | ------- | ------ | ---------- | --- | ------ | ----- | --- | --- | ---------- | ------- |
| [MLSL (Ours)](https://arxiv.org/abs/1909.13776) |WACV-2020|ST| 45.2 | 51.0 | 59.2 | 30.2 | 68.5 | 22.9 | 1.0 | 36.2 | 32.7 | 28.3 | 86.2 | 75.4 | 68.6 | 27.7 | 82.7 | 26.3 | 24.3 | 52.7 |
| [DADA](https://arxiv.org/abs/1904.01886) |ICCV-2019|Adv| 42.6 | 49.8 | 89.2 | 44.8 | 81.4 |6.8 |0.3 |26.2 |8.6 |11.1 |81.8 |84.0 |54.7 |19.3 |79.7 |40.7 |14.0 |38.8 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR-2019|Adv| 41.5 | 48.7 | 91.7 | 53.5 | 77.1 | 2.5 | 0.2 | 27.1 | 6.2 | 7.6 | 78.4 | 81.2 | 55.8 | 19.2 | 82.3 | 30.3 | 17.1 | 34.3 |
| [BDL](https://arxiv.org/abs/1904.10620) |CVPR-2019|Adv+ST| 39.0| -| 72.0| 30.3| 74.5| 0.1| 0.3| 24.6| 10.2| 25.2| 80.5| 80.0| 54.7| 23.2| 72.7| 24.0| 7.5| 44.9|
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV-2018|ST| 35.4 | 36.1 |69.6 |28.7 |69.5 |12.1 |0.1 |25.4 |11.9 |13.6 |82.0 |81.9 |49.1 |14.5 |66.0 |6.6 |3.7| 32.4|
| [DPR](https://arxiv.org/pdf/1901.05427.pdf) |ICCV-2019|Adv| 33.7| 39.6| 72.6| 29.5| 77.2| 3.5| 0.4| 21.0| 1.4| 7.9| 73.3| 79.0| 45.7| 14.5| 69.4| 19.6| 7.4| 16.5|
| [CLAN](https://arxiv.org/abs/1809.09478) |CVPR-2019|Adv| - |39.3 | 80.4| 30.7| 74.7| - | - | - | 1.4| 8.0| 77.1| 79.0| 46.5| 8.9| 73.8| 18.2| 2.2| 9.9|
| [AdaptNet](https://arxiv.org/abs/1802.10349) |CVPR-2018|Adv| - |37.6| 78.9| 29.2| 75.5| - | - | - | 0.1| 4.8| 72.6| 76.7| 43.4| 8.8| 71.1| 16.0| 3.6| 8.4|
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR-2019|Adv| 31.4| 36.6| 67.9| 29.4| 71.9| 6.3| 0.3| 19.9| 0.6| 2.6| 74.9| 74.9| 35.4| 9.6| 67.8| 21.4| 4.1| 15.5|



Where mean IoU* is over 13-classes (excluding wall, pole and fence).

An Implementation to our WACV-2020 paper "[MLSL: Multi-Level Self-Supervised Learning for Domain Adaptation with Spatially Independent and Semantically Consistent Labeling](https://arxiv.org/abs/1909.13776)" will be shortly available [here](https://github.com/engrjavediqbal/MLSL). 

### Citation:
If you found this useful, please cite our [paper](https://arxiv.org/abs/1909.13776). 

>@article{iqbal2019mlsl,  
>&nbsp; &nbsp; &nbsp;    title={MLSL: Multi-Level Self-Supervised Learning for Domain Adaptation with Spatially Independent and  
>&nbsp; &nbsp; &nbsp;     Semantically Consistent Labeling},  
>&nbsp; &nbsp; &nbsp;     author={Javed Iqbal and Mohsen Ali},  
>&nbsp; &nbsp; &nbsp;     journal={arXiv preprint arXiv:1909.13776},  
>&nbsp; &nbsp; &nbsp;     year={2019}  
>}

### Contact:
Feel free to contact  for adding your published results to leaderboard.

Contact: javed.iqbal@itu.edu.pk
