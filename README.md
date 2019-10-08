# Leaderboard for Domain Adaptation for Semantic Segmentation


## GTA-V to Cityscapes Adaptation

| Methods        | Venue | Approach        | mean IoU | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Terrain | Sky | Person | Rider | Car | Truck | Bus | Train | Motorcycle | Bicycle |
| -------------- | ----- |:---------------:| -------- | ----- | -------- | -------- | ---- | ----- | ---- | -------- | ------- | ---------- | ------- | --- | ------ | ----- | --- | ----- | --- | ----- | ---------- | ------- |
| [MLSL](https://arxiv.org/abs/1909.13776) |WACV2020|ST| 49.0 | 89.0 | 45.2 | 78.2 | 22.9 | 27.3 | 37.4 | 46.1 | 43.8 | 82.9 | 18.6 | 61.2 | 60.4 | 26.7 | 85.4 | 35.9 | 44.9 | 36.4 | 37.2 | 49.3 |
| [BDL](https://arxiv.org/abs/1904.10620) |CVPR2019|Adv+ST| 48.5 | 91.0 | 44.7 | 84.2 | 34.6 | 27.6 | 30.2 | 36.0 | 36.0 | 85.0 | 43.6 | 83.0 | 58.6 | 31.6 | 83.3 | 35.3 | 49.7 | 3.3 | 28.8 | 35.6 |
| [CRST](https://arxiv.org/abs/1908.09822) |ICCV2019|ST| 46.8 | 84.5 | 47.7 | 74.1 | 27.9 | 22.1 | 43.8 | 46.5 | 37.8 | 83.7 | 22.7 | 56.1 | 56.8 | 26.8 | 81.7 | 22.5 | 46.2 | 27.5 | 32.3 | 47.9 |
| [MaxSquare](https://arxiv.org/abs/1909.13589) |ICCV2019|Adv+ST| 46.4 | 89.4 |43.0 |82.1 |30.5 |21.3 |30.3 |34.7 |24.0 |85.3 |39.4 |78.2 |63.0 |22.9 |84.6 |36.4 |43.0 |5.5 |34.7 |33.5 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV2018|ST| 46.2 | 88.0 | 56.2 | 77.0 | 27.4 | 22.4 | 40.7 | 47.3 | 40.9 | 82.4 | 21.6 | 60.3 | 50.2 | 20.4 | 83.8 | 35.0 | 51.0 | 15.2 | 20.6 | 37.0 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR2019|Adv| 45.4 | 91.5 | 47.5 | 82.5 | 31.3 | 25.6 | 33.0 | 33.7 | 25.8 | 82.7 | 28.8 | 82.7 | 62.4 | 30.8 | 85.2 | 27.7 | 34.5 | 6.4 | 25.2 | 24.4 |
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR2019|Adv+ST| 44.8 | 87.6 | 21.4 | 82.0 | 34.8 | 26.2 | 28.5 | 35.6 | 23.0 | 84.5 | 35.1 | 76.2 | 58.6 | 30.7 | 84.8 | 34.2 | 43.4 | 0.4 | 28.4 | 35.3 |
| [DLOW](https://arxiv.org/abs/1812.05418) |CVPR2019|Adv| 42.3 | 87.1 | 33.5 | 80.5 | 24.5 | 13.2 | 29.8 | 29.5 | 26.6 | 82.6 | 26.7 | 81.8 | 55.9 | 25.3 | 78.0 | 33.5 | 38.7 | 0.0 | 22.9 | 34.5 |




## SYNTHIA to Cityscapes Adaptation

| Methods        | Venue/Year | Approach        | mean IoU | mean IoU* | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Sky | Person | Rider | Car | Bus | Motorcycle | Bicycle |
| -------------- | ---------- |:---------------:| -------- | --------- | ----- | -------- | -------- | ---- | ----- | ---- | ------- | ------ | ---------- | --- | ------ | ----- | --- | --- | ---------- | ------- |
| [MLSL](https://arxiv.org/abs/1909.13776) |WACV-2020|ST| 45.2 | 51.0 | 59.2 | 30.2 | 68.5 | 22.9 | 1.0 | 36.2 | 32.7 | 28.3 | 86.2 | 75.4 | 68.6 | 27.7 | 82.7 | 26.3 | 24.3 | 52.7 |
| [CRST](https://arxiv.org/abs/1908.09822) |ICCV-2019|ST| 43.8 | 50.1 | 67.7 | 32.2 | 73.9 | 10.7 | 1.6 | 37.4 | 22.2 | 31.2 | 80.8 | 80.5 | 60.8 | 29.1 | 82.8 | 25.0 | 19.4 | 45.3 |
| [DADA](https://arxiv.org/abs/1904.01886) |ICCV-2019|Adv| 42.6 | 49.8 | 89.2 | 44.8 | 81.4 |6.8 |0.3 |26.2 |8.6 |11.1 |81.8 |84.0 |54.7 |19.3 |79.7 |40.7 |14.0 |38.8 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ECCV-2018|ST| 42.5 | 48.4 | 53.6 | 23.7 | 75.0 | 12.5 | 0.3 | 36.4 | 23.5 | 26.3 | 84.8 | 74.7 | 67.2 | 17.5 | 84.5 | 28.4 | 15.2 | 55.8 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |CVPR-2019|Adv| 41.5 | 48.7 | 91.7 | 53.5 | 77.1 | 2.5 | 0.2 | 27.1 | 6.2 | 7.6 | 78.4 | 81.2 | 55.8 | 19.2 | 82.3 | 30.3 | 17.1 | 34.3 |
| [MaxSquare](https://arxiv.org/abs/1909.13589) |ICCV2019|Adv+ST| 41.4 | 48.2 | 82.9 | 40.7 | 80.3 | 10.2 | 0.8 | 25.8 | 12.8 | 18.2 | 82.5 | 82.2 | 53.1 | 18.0 | 79.0 | 31.4 | 10.4 | 35.6|
| [ADVENT](https://arxiv.org/abs/1811.12833) |CVPR-2019|Adv+ST| 41.2 | 48.0 | 85.6 | 42.2 | 79.7 | 8.7 | 0.4 | 25.9 | 5.4 | 8.1 | 80.4 | 84.1 | 57.9 | 23.8 | 73.3 | 36.4 | 14.2 | 33.0 |

Where mean IoU* is over 13-classes (excluding wall, pole and fence).


Feel free to contact  for adding your published results.

Contact: javed.iqbal@itu.edu.pk
