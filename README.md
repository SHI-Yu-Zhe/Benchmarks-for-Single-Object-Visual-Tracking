# Surveys

|   Dataset   |                   Source                   |  Domain  |
| :---------: | :----------------------------------------: | :------: |
|   OTB100    |         Exist Datasets(e.g. FERET)         |  People  |
|   VOT2018   |          Exist Datasets(e.g. OTB)          |  People  |
|   UAV123    |   (UAV+HD Camera; UAV+miniC; Simulator)    | Vehicles |
| TrackingNet |               Youtube(YT-BB)               | Diverse  |
|   NFS2017   |           Embedded Vision/Mobile           | High fps |
|    LaSOT    | Youtube(70 Categories defined by ImageNet) | Diverse  |

|   Dataset   |                  Evaluation Methodology                   |
| :---------: | :-------------------------------------------------------: |
|   OTB100    |    P;IoU->AOS+AUC; OPE+OPER; TRE+SRE+SRER; Vitual runs    |
|   VOT2018   | P;IoU->AOS+Re-initialized(N=5)+(Burnin=10); Per-frame A/R |
|   UAV123    |         P;IoU->AOS+AUC; OPE+OPER; SRE; Simulator          |
| TrackingNet |          P; IoU->AOS+AUC; OPE with normalization          |
|   NFS2017   |  IoU->AOS+AUC; ImprovedAccuracy/Low fpsAccuracy(240->30)  |
|    LaSOT    |                   P; IoU->AOS+AUC; OPE                    |

|      | OTB100 | VOT2018 | UAV123 | TrackingNet | NFS2017 | LaSOT |
| ---- | ------ | ------- | ------ | ----------- | ------- | ----- |
| CM   |        | 1       | 1      | 1           |         | 1     |
| IPR  | 1      |         |        | 1           |         | 1     |
| OPR  | 1      |         |        | 1           |         |       |
| DEF  | 1      | 1       |        | 1           | 1       | 1     |
| FOC  | 1      |         | 1      | 1           | 1       | 1     |
| POC  | 1      |         | 1      | 1           | 1       | 1     |
| IV   | 1      | 1       | 1      | 1           | 1       | 1     |
| OV   | 1      |         | 1      | 1           | 1       | 1     |
| VC   |        |         | 1      |             | 1       | 1     |
| SV   | 1      | 1       | 1      | 1           | 1       | 1     |
| MB   | 1      | 1       |        | 1           |         | 1     |
| ARC  |        | 1       | 1      | 1           |         | 1     |
| LR   | 1      |         | 1      | 1           | 1       | 1     |
| FM   | 1      |         | 1      | 1           | 1       | 1     |
| BC   | 1      | 1       | 1      | 1           | 1       | 1     |
| SOB  |        |         | 1      | 1           |         |       |

