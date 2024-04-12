# QGRL: Quaternion Graph Representation Learning for Heterogeneous Feature Data Clustering
## 1. $t$-SNE Visualization of Representative Methods on Seven Comprehensive Data sets

![tsne](tsne.png)

## 2. Supplementary Results of Table 2

| Data set | Metric |   K-Means   |     SC      | GAE         |    VGAE     |      ARGAE      |   ARVGAE    |    CCGC     |      DFCN       |    DAEGC    |      EGAE       |      Ours       |
| :------: | :----: | :---------: | :---------: | ----------- | :---------: | :-------------: | :---------: | :---------: | :-------------: | :---------: | :-------------: | :-------------: |
|    HF    |   F1   | 0.4646±0.00 | 0.4032±0.00 | 0.5400±0.00 | 0.5111±0.01 |   0.4883±0.00   | 0.4915±0.01 | 0.5404±0.00 |   0.5026±0.01   | 0.4253±0.03 |   0.0002±0.00   | **0.6788±0.04** |
|    BC    |   F1   | 0.4984±0.00 | 0.3613±0.00 | 0.6465±0.00 | 0.4994±0.02 |   0.5222±0.01   | 0.5380±0.00 | 0.6547±0.33 |   0.5361±0.04   | 0.4115±0.00 |   0.4743±0.09   | **0.6657±0.00** |
|    AA    |   F1   | 0.4898±0.01 | 0.4970±0.00 | 0.4756±0.00 | 0.4901±0.06 | **0.5946±0.00** | 0.5321±0.01 | 0.5620±0.02 |   0.5065±0.01   | 0.4000±0.01 |   0.4140±0.03   |   0.4476±0.03   |
|    MM    |   F1   | 0.5186±0.00 | 0.3365±0.00 | 0.5034±0.00 | 0.5101±0.01 |   0.6244±0.00   | 0.5250±0.01 | 0.6819±0.02 |   0.6848±0.00   | 0.3958±0.09 |   0.8277±0.00   | **0.8326±0.00** |
|    ZO    |   F1   | 0.4515±0.03 | 0.0704±0.00 | 0.5134±0.01 | 0.2140±0.02 |   0.2799±0.00   | 0.2820±0.00 | 0.5683±0.03 | **0.6334±0.05** | 0.1040±0.02 |   0.5479±0.02   |   0.6184±0.04   |
|   TTT    |   F1   | 0.5146±0.00 | 0.3948±0.00 | 0.5599±0.00 | 0.4963±0.01 |   0.5650±0.00   | 0.5575±0.00 | 0.5633±0.01 |   0.5183±0.01   | 0.3976±0.01 |   0.4207±0.08   | **0.9572±0.02** |
|    GI    |   F1   | 0.2948±0.00 | 0.3651±0.00 | 0.3489±0.01 | 0.2095±0.01 |   0.2380±0.01   | 0.2022±0.01 | 0.3646±0.03 |   0.4457±0.01   | 0.0960±0.01 |   0.4747±0.01   | **0.4961±0.03** |
|    YE    |   F1   | 0.2433±0.01 | 0.0484±0.00 | 0.2263±0.01 | 0.1053±0.01 |   0.2414±0.00   | 0.2397±0.00 | 0.2017±0.00 |   0.1822±0.01   | 0.0551±0.01 | **0.2845±0.02** |   0.2138±0.02   |
|    II    |   F1   | 0.8080±0.00 | 0.1814±0.00 | 0.7823±0.00 | 0.3708±0.03 |   0.4411±0.00   | 0.3810±0.01 | 0.9237±0.01 |   0.8277±0.02   | 0.1814±0.00 |   0.9191±0.01   | **0.9559±0.01** |
|    WI    |   F1   | 0.4832±0.00 | 0.2025±0.00 | 0.2736±0.00 | 0.2977±0.02 |   0.4028±0.01   | 0.3596±0.00 | 0.5380±0.02 |   0.4735±0.01   | 0.2027±0.00 |   0.7466±0.00   | **0.9641±0.00** |



| Data set | Metric |   K-Means   |     SC      | GAE         |     VGAE     |    ARGAE    |   ARVGAE    |    CCGC     |    DFCN     |    DAEGC    |      EGAE       |      Ours       |
| :------: | :----: | :---------: | :---------: | ----------- | :----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :-------------: | :-------------: |
|    HF    | Purity | 0.6923±0.00 | 0.6789±0.00 | 0.6789±0.00 | 0.6789±0.00  | 0.6789±0.00 | 0.6789±0.00 | 0.6789±0.00 | 0.6789±0.00 | 0.6819±0.00 |   0.1814±0.00   | **0.7130±0.03** |
|    BC    | Purity | 0.7028±0.00 | 0.6534±0.00 | 0.7098±0.00 | 0.7028±0.00  | 0.7028±0.00 | 0.7028±0.00 | 0.7098±0.00 | 0.7028±0.00 | 0.7028±0.00 |   0.7028±0.00   | **0.7203±0.00** |
|    AA    | Purity | 0.6058±0.00 | 0.6058±0.00 | 0.6058±0.00 | 0.6058±0.00  | 0.6125±0.01 | 0.6058±0.00 | 0.6058±0.00 | 0.6058±0.00 | 0.6144±0.00 |   0.6154±0.00   | **0.6298±0.01** |
|    MM    | Purity | 0.5606±0.01 | 0.5145±0.00 | 0.5337±0.00 | 0.5145±0.00  | 0.6348±0.04 | 0.5559±0.01 | 0.6783±0.00 | 0.6855±0.00 | 0.5267±0.03 |   0.8277±0.00   | **0.8327±0.00** |
|    ZO    | Purity | 0.7317±0.01 | 0.4059±0.00 | 0.7525±0.00 | 0.4257±0.00  | 0.4614±0.01 | 0.4446±0.01 | 0.7525±0.00 | 0.8178±0.04 | 0.4198±0.01 |   0.7624±0.00   | **0.8376±0.02** |
|   TTT    | Purity | 0.6534±0.00 | 0.6534±0.00 | 0.6534±0.00 | 0.6534±0.00  | 0.6534 0.00 | 0.6534 0.00 | 0.6534±0.00 | 0.6534±0.00 | 0.6534±0.00 |   0.6534±0.00   | **0.9606±0.02** |
|    GI    | Purity | 0.4486±0.00 | 0.5224±0.00 | 0.4907±0.00 | 0.3972±0.00  | 0.3986±0.02 | 0.3813±0.01 | 0.5140±0.00 | 0.5117±0.01 | 0.3776±0.00 |   0.6262±0.00   | **0.7009±0.05** |
|    YE    | Purity | 0.3550±0.01 | 0.3140±0.00 | 0.3544±0.00 | 0.3221±0.00  | 0.3567±0.00 | 0.3569±0.00 | 0.3551±0.00 | 0.4060±0.01 | 0.3172±0.00 | **0.5027±0.00** |   0.4369±0.02   |
|    II    | Purity | 0.8200±0.00 | 0.3467±0.00 | 0.8000±0.00 | 0.3933±0.00  | 0.4480±0.02 | 0.3980±0.01 | 0.8933±0.00 | 0.8373±0.01 | 0.3467±0.00 |   0.9267±0.00   | **0.9560±0.01** |
|    WI    | Purity | 0.5337±0.00 | 0.4045±0.00 | 0.4101±0.00 | 0.43.26±0.00 | 0.4163±0.01 | 0.3596±0.00 | 0.5562±0.00 | 0.5348±0.01 | 0.4101±0.00 |   0.7472±0.00   | **0.9640±0.00** |
