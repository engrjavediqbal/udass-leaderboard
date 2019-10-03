# Leaderboard for Domain Adaptation for Semantic Segmentation


## GTA-V to Cityscapes Adaptation

| Methods        | Approach        | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Terrain | Sky | Person | Rider | Car | Truck | Bus | Train | Motorcycle | Bicycle | mean IoU |
| -------------- |:---------------:| ----- | -------- | -------- | ---- | ----- | ---- | -------- | ------- | ---------- | ------- | --- | ------ | ----- | --- | ----- | --- | ----- | ---------- | ------- | -------- |
| [MLSL](https://arxiv.org/abs/1909.13776) |ST| 89.0 | 45.2 | 78.2 | 22.9 | 27.3 | 37.4 | 46.1 | 43.8 | 82.9 | 18.6 | 61.2 | 60.4 | 26.7 | 85.4 | 35.9 | 44.9 | 36.4 | 37.2 | 49.3 | 49.0 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ST| 88.0 | 56.2 | 77.0 | 27.4 | 22.4 | 40.7 | 47.3 | 40.9 | 82.4 | 21.6 | 60.3 | 50.2 | 20.4 | 83.8 | 35.0 | 51.0 | 15.2 | 20.6 | 37.0 | 46.2 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |Adv| 91.5 | 47.5 | 82.5 | 31.3 | 25.6 | 33.0 | 33.7 | 25.8 | 82.7 | 28.8 | 82.7 | 62.4 | 30.8 | 85.2 | 27.7 | 34.5 | 6.4 | 25.2 | 24.4 | 45.4 |



## SYNTHIA to Cityscapes Adaptation

| Methods        | Approach        | Road  | Sidewalk | Building | Wall | Fence | Pole | T.Light | T.Sign | Vegitation | Sky | Person | Rider | Car | Bus | Motorcycle | Bicycle | mean IoU | mean IoU* |
| -------------- |:---------------:| ----- | -------- | -------- | ---- | ----- | ---- | ------- | ------ | ---------- | --- | ------ | ----- | --- | --- | ---------- | ------- | -------- | --------- |
| [MLSL](https://arxiv.org/abs/1909.13776) |ST| 59.2 | 30.2 | 68.5 | 22.9 | 1.0 | 36.2 | 32.7 | 28.3 | 86.2 | 75.4 | 68.6 | 27.7 | 82.7 | 26.3 | 24.3 | 52.7 | 45.2 | 51.0 |
| [CBST](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Zou_Unsupervised_Domain_Adaptation_ECCV_2018_paper.pdf) |ST| 53.6 | 23.7 | 75.0 | 12.5 | 0.3 | 36.4 | 23.5 | 26.3 | 84.8 | 74.7 | 67.2 | 17.5 | 84.5 | 28.4 | 15.2 | 55.8 | 42.5 | 48.4 |
| [All_Structure](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_All_About_Structure_Adapting_Structural_Information_Across_Domains_for_Boosting_CVPR_2019_paper.pdf) |Adv| 91.7 | 53.5 | 77.1 | 2.5 | 0.2 | 27.1 | 6.2 | 7.6 | 78.4 | 81.2 | 55.8 | 19.2 | 82.3 | 30.3 | 17.1 | 34.3 | 41.5 | 48.7 |

Where mean IoU* is over 13-classes (excluding wall, pole and fence).
