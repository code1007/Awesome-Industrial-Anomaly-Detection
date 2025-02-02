# Awesome-Industrial-Anomaly-Detection

Welcome to our GitHub page 😄

Here, we have gathered the latest research papers, datasets, and experimental results related to **circuit boards** in the field of anomaly detection. Anomaly detection is a crucial direction in data science and machine learning, with broad applications in various real-world domains such as financial risk control, medical diagnosis, and cybersecurity.

We hope that by organizing and sharing these resources, we can provide assistance and inspiration for research and projects in related fields. Your valuable feedback and suggestions are always welcome!

The page is created by the Qi Jia Lab at Dalian University of Technology 🏫, with major contributors Qiuhan Bo :girl: and Pengshuo Zhang :boy:. :kissing_heart: :kissing_heart: :kissing_heart: 

## 内容说明
|  Title  |   Venue  |   Code   | Datasets |  Method  |Experiments|
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
|论文标题名，带PDF链接| 发表会议/期刊，缩写|代码链接，如无，则-|数据集对应下方Datasets表格,若没有，则补充进Datasets表格|全监督/半监督/自监督/教师学生等|评价指标及对应数值/训练时间/测试时间，可以截图也可文字，截图需把评价指标（AUC等）/数据集等信息截全，文字也需如此（xx数据集上xx指标达到xx）|

## 2025 :heart_eyes:	
|  Title  |   Venue  |   Code   | Datasets |  Method  |Experiments|
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
|[**Anomaly Detection via Reverse Distillation from One-Class Embedding**](https://openaccess.thecvf.com/content/CVPR2022/html/Deng_Anomaly_Detection_via_Reverse_Distillation_From_One-Class_Embedding_CVPR_2022_paper.html) <br> | CVPR | [Github](https://github.com/hq-deng/RD4AD) | [MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad)| Semi-supervised & Teacher-student ![image](https://github.com/YAOSL98/Awesome-Industrial-Anomaly-Detection/blob/main/sample2.png)|**1. Evaluation metrics and accuracy:** MVTec数据集上AUC98.5%![image](https://github.com/YAOSL98/Awesome-Industrial-Anomaly-Detection/blob/main/sample.png)<br> **2. Computational cost:** 训练时间无，测试时间0.31s/张|
|         |          |          |          |          |          |
|         |          |          |          |          |          |
|         |          |          |          |          |          |



## 2024 :kissing_closed_eyes:	
|  Title  |   Venue  |   Code   | Datasets |  Method  |Experiments|
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| [**Implicit Foreground-Guided Network for Anomaly Detection and Localization**](https://ieeexplore.ieee.org/abstract/document/10446952) |  ICASSP  |    -    |   [VisA](https://github.com/amazon-science/spot-diff)  |  [full-supervised]![image](https://github.com/YAOSL98/Awesome-Industrial-Anomaly-Detection/blob/main/ICASSP2024-1-1.png)  | **1. Evaluation metrics and accuracy:** VisA数据集上AUC98.4%![image](https://github.com/YAOSL98/Awesome-Industrial-Anomaly-Detection/blob/main/ICASSP2024-1-2.png)<br> **2. Computational cost:** 训练时间无，测试时间无         |
|         |          |          |          |          |          |
|         |          |          |          |          |          |
|         |          |          |          |          |          |


## 2023 :laughing:	
|  Title  |   Venue  |   Code   | Datasets |  Method  |Experiments|
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
|         |          |          |          |          |          |
|         |          |          |          |          |          |
|         |          |          |          |          |          |
|         |          |          |          |          |          |



## Dataset
|Important Dataset|示例图|中文简介|
|---|---|---|
|[VisA](https://github.com/amazon-science/spot-diff)|![image](https://github.com/YAOSL98/Awesome-Industrial-Anomaly-Detection/blob/main/VisA.png)|VisA 数据集是用于异常检测和分割的数据集。包含 12 个子集，对应 12 个不同的对象，如图所示。有 10,821 张图像，其中 9,621 个正常样本和 1,200 个异常样本。四个子集是不同类型的印刷电路板 (PCB），其结构相对复杂，包含晶体管、电容器、芯片等。对于视图中多个实例的情况，我们收集四个子集：Capsules 、 Candles 、 Macaroni1 和 Macaroni2 。 Capsules 和 Macaroni2 中的实例在位置和姿势上有很大不同。此外，研究团队还收集了四个子集，包括腰果、口香糖、炸薯条和管道炸薯条，其中对象大致对齐。异常图像包含各种缺陷，包括划痕、凹痕、色斑或裂纹等表面缺陷，以及错位或缺失部件等结构缺陷。|
|[CD-PCB](https://github.com/Scientific-Computing-Lab/ChangeChip)|![image](https://github.com/YAOSL98/Awesome-Industrial-Anomaly-Detection/blob/main/CD-PCB.png)|一个包含 20 对 PCB 图像的小型数据集，其中标注了它们之间的变化。该数据集旨在评估 PCB 检查领域的变化检测算法。|
|[PKU-Market-PCB](https://robotics.pkusz.edu.cn/resources/dataset/)|![image](https://github.com/YAOSL98/Awesome-Industrial-Anomaly-Detection/blob/main/PKU-Market-PCB.png)|北京大学收集，包含1386张图像以及6种缺陷（缺失孔，老鼠咬坏，开路，短路，杂散，伪铜）|

| Dataset                | Class | Normal | Abnormal | Total  | Annotation level  | Source                | Time         |
|------------------------|-------|--------|----------|--------|-------------------|-----------------------|--------------|
| [VisA](https://github.com/amazon-science/spot-diff)                   | 12    | 9621   | 1200     | 10821  | Segmentation mask | RGB real         | ECCV,2022    |
| [AITEX](https://www.cvmart.net/dataSets/detail/300)                  | 1     | 140    | 105      | 245    | Segmentation mask | RGB real         | 2019         |
| [Anomaly-ShapeNet](https://github.com/Chopper-233/Anomaly-ShapeNet)       | 40    | -      | -        | 1600   | Point-level mask  | Point-cloud synthetic | CVPR,2024    |
| [BTAD](http://avires.dimi.uniud.it/papers/btad/btad.zip)                   | 3     | -      | -        | 2830   | Segmentation mask | RGB real         | 2021         |
| [CID](https://github.com/LightZH/Insulator-Defect-Detection) | 1 | 4060 | 233 | 4293 | Segmentation mask | RGB real | 2024,TIM | 
| [DAGM](https://www.kaggle.com/datasets/mhskjelvareid/dagm-2007-competition-dataset-optical-inspection)                   | 10    | -      | -        | 11500  | Segmentation mask | RGB synthetic     | 2007         |
| [DEEPPCB](https://github.com/tangsanli5201/DeepPCB)                | 1     | -      | -        | 1500   | Bounding box      | RGB synthetic     | 2019         |
| [DTD-Synthetic](https://drive.google.com/drive/folders/10OyPzvI3H6llCZBxKxFlKWt1Pw1tkMK1)          | 12    | -      | -        | -      | Segmentation mask | RGB synthetic     | WACV,2024    |
| [Eyecandies](https://eyecan-ai.github.io/eyecandies/)             | 10    | 13250  | 2250     | 15500  | Segmentation mask | RGBD synthetic image  | ACCV,2022    |
| [Fabirc dataset](http://hub.hku.hk/bitstream/10722/229176/1/content.pdf)         | 1     | 25     | 25       | 50     | Segmentation mask | RGB synthetic     | PR,2016      |
| [GDXray](https://domingomery.ing.puc.cl/material/gdxray/)                 | 1     | 0      | 19407    | 19407  | Bounding box      | RGB real         | 2016         |
| [IPAD](https://ljf1113.github.io/IPAD_VAD/) | 16 | - | - | 597979 | Image | Video real&synthetic | 2024 |
| [KolekrotSDD](https://www.vicos.si/resources/kolektorsdd/)            | 1     | 347    | 52       | 399    | Segmentation mask | RGB real         | JIM,2019     |
| [KolekrotSDD2](https://www.vicos.si/resources/kolektorsdd2/)           | 1     | 2979   | 356      | 3335   | Segmentation mask | RGB real         | CiI,2021     |
| [MIAD](https://miad-2022.github.io/)                   | 7     | 87500  | 17500    | 105000 | Segmentation mask | RGB synthetic     | 2023         |
| [MPDD](https://github.com/stepanje/MPDD)                   | 6     | 1064   | 282      | 1346   | Segmentation mask | RGB real         | ICUMT,2021   |
| [MTD](https://github.com/abin24/Magnetic-tile-defect-datasets.) | 1 | 952 | 392 | 1344 | Segmentation mask | RGB real | CASE,2018 |
| [MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad)               | 15    | 4096   | 1258     | 5354   | Segmentation mask | RGB real         | CVPR,2019    |
| [MVTec 3D-AD](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)            | 10    | 2904   | 948      | 3852   | Segmentation mask | RGB real          | VISAPP,2021  |
| [MVTec LOCO-AD](https://www.mvtec.com/company/research/datasets/mvtec-loco)          | 5     | 2347   | 993      | 3340   | Segmentation mask | RGBD real       | IJCV,2022    |
| [NanoTwice](http://web.mi.imati.cnr.it/ettore/NanoTwice)              | 1     | 5      | 40       | 45     | Segmentation mask | RGB real         | TII,2016     |
| [NEU surface defect](http://faculty.neu.edu.cn/songkechen/zh_CN/zdylm/263270/list/index.htm)     | 1     | 0      | 1800     | 1800   | Bounding box      | RGB real         | 2013         |
| [PAD](https://github.com/EricLee0224/PAD)                    | 20    | 5231   | 4902     | 10133  | Segmentation mask | RBG synthetic    | NeurIPS,2023 |
| [Real-IAD](https://realiad4ad.github.io/Real-IAD/)               | 30    | 99721  | 51329    | 151050 | Segmentation mask | RGB real         | CVPR,2024    |
| [Real3D-AD](https://github.com/M-3LAB/Real3D-AD)              | 12    | 652    | 602      | 1254   | Point-level mask  | Point-cloud real       | NeurIPS,2023 |
| [RSDD](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8063875)                   | 2     | -      | -        | 195    | Segmentation mask | RGB real         | 2017         |
| [Steel defect detection](https://www.kaggle.com/code/ekhtiar/resunet-a-baseline-on-tensorflow/notebook) | 1     | -      | -        | 18076  | Image             | RGB real         | 2019         |
| [Steel tube dataset](https://github.com/huangyebiaoke/steel-pipe-weld-defect-detection)     | 1     | 0      | 3408     | 3408   | Bounding box      | RGB real         | 2021         |
| [RAD](https://github.com/hustCYQ/RAD-dataset)                   | 4    | 213   | 1224     | 1224  | Segmentation mask | RGB real         | CASE,2024    |

