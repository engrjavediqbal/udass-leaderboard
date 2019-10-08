# Leaderboard for Domain Adaptation for Semantic Segmentation


Synthetic to real domain adaptation is a standard setup used in state-of-the-art methods recently. Below two leaderboards for GTA-V to Cityscapes and SYNTHIA to Cityscapes are shown. Each paper is represented with its nickname, venue and year of publication. The approchares used in different papers are abbrevated as "ST" for Self-training or self-supervised learning and "Adv" for adversarial learning respectively. The papers are in descending order with respect to mean Intersection over Union (mean IoU). 


## GTA-V to Cityscapes Adaptation

| Methods        | Venue/Year | Approach        | mean IoU | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Terrain | Sky | Person | Rider | Car | Truck | Bus | Train | Motorcycle | Bicycle |
| -------------- | ----- |:---------------:| -------- | ----- | -------- | -------- | ---- | ----- | ---- | -------- | ------- | ---------- | ------- | --- | ------ | ----- | --- | ----- | --- | ----- | ---------- | ------- |
| [MLSL (Ours)](https://arxiv.org/abs/1909.13776) |WACV-2020|ST| 49.0 | 89.0 | 45.2 | 78.2 | 22.9 | 27.3 | 37.4 | 46.1 | 43.8 | 82.9 | 18.6 | 61.2 | 60.4 | 26.7 | 85.4 | 35.9 | 44.9 | 36.4 | 37.2 | 49.3 |
| [BDL](https://arxiv.org/abs/1904.10620) |CVPR-2019|Adv+ST| 48.5 | 91.0 | 44.7 | 84.2 | 34.6 | 27.6 | 30.2 | 36.0 | 36.0 | 85.0 | 43.6 | 83.0 | 58.6 | 31.6 | 83.3 | 35.3 | 49.7 | 3.3 | 28.8 | 35.6 |
| [CRST](https://arxiv.org/abs/1908.09822) |ICCV-2019|ST| 46.8 | 84.5 | 47.7 | 74.1 | 27.9 | 22.1 | 43.8 | 46.5 | 37.8 | 83.7 | 22.7 | 56.1 | 56.8 | 26.8 | 81.7 | 22.5 | 46.2 | 27.5 | 32.3 | 47.9 |
| [MaxSquare](https://arxiv.org/abs/1909.13589) |ICCV-2019|Adv+ST| 46.4 | 89.4 |43.0 |82.1 |30.5 |21.3 |30.3 |34.7 |24.0 |85.3 |39.4 |78.2 |63.0 |22.9 |84.6 |36.4 |43.0 |5.5 |34.7 |33.5 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV-2018|ST| 46.2 | 88.0 | 56.2 | 77.0 | 27.4 | 22.4 | 40.7 | 47.3 | 40.9 | 82.4 | 21.6 | 60.3 | 50.2 | 20.4 | 83.8 | 35.0 | 51.0 | 15.2 | 20.6 | 37.0 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR-2019|Adv| 45.4 | 91.5 | 47.5 | 82.5 | 31.3 | 25.6 | 33.0 | 33.7 | 25.8 | 82.7 | 28.8 | 82.7 | 62.4 | 30.8 | 85.2 | 27.7 | 34.5 | 6.4 | 25.2 | 24.4 |
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR-2019|Adv+ST| 44.8 | 87.6 | 21.4 | 82.0 | 34.8 | 26.2 | 28.5 | 35.6 | 23.0 | 84.5 | 35.1 | 76.2 | 58.6 | 30.7 | 84.8 | 34.2 | 43.4 | 0.4 | 28.4 | 35.3 |
| [CLAN](https://arxiv.org/abs/1809.09478) |CVPR-2019|Adv| 43.2 | 87.0 | 27.1 | 79.6 | 27.3 | 23.3 | 28.3 | 35.5 | 24.2 | 83.6 | 27.4 | 74.2 | 58.6 | 28.0 | 76.2 | 33.1 | 36.7 | 6.7 | 31.9 | 31.4 |
| [Saleh etal](https://arxiv.org/abs/1807.06132) |ECCV-2018|Adv| 42.5 | 79.8 | 29.3 | 77.8 | 24.2 | 21.6 | 6.9 | 23.5 | 44.2 | 80.5 | 38.0 | 76.2 | 52.7 | 22.2 | 83.0 | 32.3 | 41.3 | 27.0 | 19.3 | 27.7 |
| [AdaptNet](https://arxiv.org/abs/1802.10349) |CVPR-2018|Adv| 42.4 | 86.5 | 36.0 | 79.9 | 23.4 | 23.3 | 23.9 | 35.2 | 14.8 | 83.4 | 33.3 | 75.6 | 58.5 | 27.6 | 73.7 | 32.5 | 35.4 | 3.9 | 30.1 | 28.1 |
| [DLOW](https://arxiv.org/abs/1812.05418) |CVPR-2019|Adv| 42.3 | 87.1 | 33.5 | 80.5 | 24.5 | 13.2 | 29.8 | 29.5 | 26.6 | 82.6 | 26.7 | 81.8 | 55.9 | 25.3 | 78.0 | 33.5 | 38.7 | 0.0 | 22.9 | 34.5 |




## SYNTHIA to Cityscapes Adaptation

| Methods        | Venue/Year | Approach        | mean IoU | mean IoU* | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Sky | Person | Rider | Car | Bus | Motorcycle | Bicycle |
| -------------- | ---------- |:---------------:| -------- | --------- | ----- | -------- | -------- | ---- | ----- | ---- | ------- | ------ | ---------- | --- | ------ | ----- | --- | --- | ---------- | ------- |
| [MLSL (Ours)](https://arxiv.org/abs/1909.13776) |WACV-2020|ST| 45.2 | 51.0 | 59.2 | 30.2 | 68.5 | 22.9 | 1.0 | 36.2 | 32.7 | 28.3 | 86.2 | 75.4 | 68.6 | 27.7 | 82.7 | 26.3 | 24.3 | 52.7 |
| [CRST](https://arxiv.org/abs/1908.09822) |ICCV-2019|ST| 43.8 | 50.1 | 67.7 | 32.2 | 73.9 | 10.7 | 1.6 | 37.4 | 22.2 | 31.2 | 80.8 | 80.5 | 60.8 | 29.1 | 82.8 | 25.0 | 19.4 | 45.3 |
| [DADA](https://arxiv.org/abs/1904.01886) |ICCV-2019|Adv| 42.6 | 49.8 | 89.2 | 44.8 | 81.4 |6.8 |0.3 |26.2 |8.6 |11.1 |81.8 |84.0 |54.7 |19.3 |79.7 |40.7 |14.0 |38.8 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV-2018|ST| 42.5 | 48.4 | 53.6 | 23.7 | 75.0 | 12.5 | 0.3 | 36.4 | 23.5 | 26.3 | 84.8 | 74.7 | 67.2 | 17.5 | 84.5 | 28.4 | 15.2 | 55.8 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR-2019|Adv| 41.5 | 48.7 | 91.7 | 53.5 | 77.1 | 2.5 | 0.2 | 27.1 | 6.2 | 7.6 | 78.4 | 81.2 | 55.8 | 19.2 | 82.3 | 30.3 | 17.1 | 34.3 |
| [MaxSquare](https://arxiv.org/abs/1909.13589) |ICCV-2019|Adv+ST| 41.4 | 48.2 | 82.9 | 40.7 | 80.3 | 10.2 | 0.8 | 25.8 | 12.8 | 18.2 | 82.5 | 82.2 | 53.1 | 18.0 | 79.0 | 31.4 | 10.4 | 35.6|
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR-2019|Adv+ST| 41.2 | 48.0 | 85.6 | 42.2 | 79.7 | 8.7 | 0.4 | 25.9 | 5.4 | 8.1 | 80.4 | 84.1 | 57.9 | 23.8 | 73.3 | 36.4 | 14.2 | 33.0 |
| [CLAN](https://arxiv.org/abs/1809.09478) |CVPR-2019|Adv| - | 47.8 | 81.3 | 37.0 | 80.1 | -|-|-|16.1 | 13.7 | 78.2 | 81.5 | 53.4 | 21.2 | 73.0 | 32.9 | 22.6 | 30.7 |
| [AdaptNet](https://arxiv.org/abs/1802.10349) |CVPR-2018|Adv| - | 46.7 | 84.3 | 42.7 | 77.5 | -|-|-|4.7 | 7.0 | 77.9 | 82.5 | 54.3 | 21.0 | 72.3 | 32.2 | 18.9 | 32.3 |

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
