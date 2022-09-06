# Event-TKG-papers
### Paper and Code for <span style="color: red">**Event**</span>  Temporal Knowledge Graph with <span style="color: red">**Textual Data**</span> [TBD...]

| Method | Conference | Paper | Code | Datasets | Tasks |
| :----: | :----: | :----: | :----: | :----: | :----: |
| DynamicGDN | KDD19 | [paper](https://yue-ning.github.io/docs/KDD19-dengA.pdf) | [code](https://github.com/amy-deng/DynamicGCN) | ICEWS (4 countries) | Event type, Interpretability |
| Glean | KDD20 | [paper](https://par.nsf.gov/servlets/purl/10216903) | [code](https://github.com/amy-deng/glean) | ICEWS (5 countries) | Event type, Actor, Interpretability |
| CMF | CIKM 21| [paper](https://yue-ning.github.io/docs/CIKM21_cmf.pdf) | - | ICEWS (2 countries), GDELT (2 countries), Covid-19 | Event type, Explanation |
| ECOLA | arXiv 22.05 | [paper](https://arxiv.org/abs/2203.09590) | - | Reformated version of GDELT, DuEE, Wiki | Link (Interpolation, not forecasting) |

<br/>

### Paper and Code for <span style="color: red">**Event**</span> Temporal Knowledge Graph [TBD...]

- **Paper**

| Method | Conference | Paper | Code | Datasets | Tasks |
| :----: | :----: | :----: | :----: | :----: | :----: |
| Know-Evolve | ICML17 | [paper](https://dl.acm.org/doi/10.5555/3305890.3306039) | [code](https://github.com/rstriv/Know-Evolve) | ICEWS14, ICEWS-500, GDELT(2015-2016) | Link, Time |
| DyRep | ICLR19 | [paper](https://openreview.net/forum?id=HyePrhR5KX) | [code](https://github.com/Harryi0/dyrep_torch) | Social Evolution Dataset, Github Dataset | Link, Time |
| RE-Net | EMNLP20 | [paper](https://arxiv.org/abs/1904.05530) | [code](https://github.com/INK-USC/RE-Net) | ICEWS14, ICEWS18, GDELT(2018.01), WIKI, YAGO | Link |
| EvoKG | WSDM22| [paper](https://arxiv.org/abs/2202.07648) | [code](https://github.com/NamyongPark/EvoKG)| ICEWS14, ICEWS18, GDELT(2018.01), WIKI, YAGO | Link, Time |
| xERTE | ICLR21 | [paper](https://arxiv.org/abs/2012.15537)| [code](https://github.com/TemporalKGTeam/xERTE) | ICEWS14, ICEWS05-15, ICEWS18, YAGO | Link |
| CyGNet | AAAI21 | [paper](https://arxiv.org/abs/2012.08492) | [code](https://github.com/CunchaoZ/CyGNet) | ICEWS14, ICEWS18, GDELT(2018.01), WIKI, YAGO | Link |
| CluSTeR | ACL21 | [paper](https://aclanthology.org/2021.acl-long.365.pdf) | - | ICEWS14, ICEWS18, ICEWS05-15, GDELT(2018.01) | Link, Interpretability |
| TITer| EMNLP21 | [paper](https://aclanthology.org/2021.emnlp-main.655.pdf) | [code](https://github.com/jhl-hust/titer) | ICEWS14, ICEWS18, WIKI, YAGO | Link, Inductive inference, Interpretability |
| TANGO | EMNLP21 | [paper](https://arxiv.org/abs/2101.05151) | [code](https://github.com/temporalkgteam/tango) | ICEWS14, ICEWS18, ICEWS05-15, ICEWS05-15_continuous, WIKI, YAGO | Link, Inductive link, Long horizontal link |
| RE-GCN | SIGIR21 | [paper](https://dl.acm.org/doi/10.1145/3404835.3462963) | [code](https://github.com/Lee-zix/RE-GCN) | ICEWS14, ICEWS18, ICEWS05-15, GDELT(2018.01), WIKI, YAGO | Link, Event type |
| CEN | ACL22 Short | [paper](https://aclanthology.org/2022.acl-short.32/) | [code](https://github.com/lee-zix/cen) | ICEWS14, ICEWS18, WIKI | Link (online/ offline) |

- **Survey**

| Survey | Conference | Paper |
| :----: | :----: | :----: |
|What is Event Knowledge Graph: A Survey| TKDE22 | [paper](https://arxiv.org/abs/2112.15280) |


- **Reseach Group**

| Group| Related Websites | Works |
| :----: | :----: |  :----: | 
| Deng Songgaojun (Ning Yue) @ Stevens Institute of Technology | [github](https://github.com/amy-deng) | DynamicGCN, Glean, CMF, CAPE |
| TemporalKG Team (Volker Tresp) @ LMU Munich| [github](https://github.com/TemporalKGTeam?tab=repositories), [Prof's dblp](https://dblp.org/pid/t/VolkerTresp.html), [member's Stars](https://github.com/ZifengDing?tab=stars)| **Expolation**: DyERNIE, xERTE, TITer, TANGO, TEE, TLogic; **Interpolation**: TempCaps; **Text**: ECOLA; **Application**: FORCASE-TKGQA, MOST |
| Li Zixuan (Jin XiaoLong) @ Chinese Academy of Sciences | [github](https://github.com/Lee-zix) | CluSTeR, RE-GCN, CEN |

- **Raw Data Website**

| Datasets| Link |
| :----: | :----: |
| Raw data for Yago15k, Wikidata, ICEWS14, ICEWS05-15 | [github](https://github.com/mniepert/mmkb/tree/master/TemporalKGs) |
| RE-Net version ICEWS14, ICEWS18, GDELT(2018.01), WIKI, YAGO | [github](https://github.com/INK-USC/RE-Net/tree/master/data) |
| TANGO version ICEWS05-15| [github](https://github.com/TemporalKGTeam/TANGO/tree/master/ICEWS05-15) |

- **Other**

|Application| Method | Conference | Paper | Code | Datasets | Tasks |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| QA on TKG | FORECAST-TKGQA | arXiv 22.08 | [paper](https://arxiv.org/abs/2208.06501) | - |
| One-shot | OAT | AKBC21 | [arXiv](https://arxiv.org/pdf/2010.12144v1.pdf), [openreview](https://openreview.net/forum?id=GF8wO8MFQOr) | [code](https://openreview.net/forum?id=GF8wO8MFQOr) | [one-short version](https://openreview.net/forum?id=GF8wO8MFQOr) of ICEWS14, ICEWS17, GDELT 2018.01 | Link
| One-shot | MOST | arXiv 22.05 | [paper](https://arxiv.org/abs/2205.10621) | - | new but NA

### **General Review for Current Work**
1. Model continuous event time -> *can do both **Entity** and **Time** prediction*
    * Use Temporal Point Process (TPP)
        - Know-Evolve
        - DyRep
    * Use ODE (Neural Ordinary Defferential Equation)
        - TANGO
2. Aggregation + RNN Encoder -> ***Link** Prediction*
    * RE-NET
    * Evo-KG (separately design **time** prediction)
3. Retrieve related hostorical facts -> ***Link** prediction, **Interpretability**, **Inductive inference***
    * triplet facts*
        - CyGNet
    * Use RL to search path (1-2 hop evidence chain)
        - CluSTeR
        - TITer
    * subgraph
        - xERTE
4. Enhance entity & **relation** representation first -> ***Link** and **Relation** prediction*
    * RE-GCN (evolution for entity & relation embedding)
    * Glean (use word graph from texual data to enrich entity & relation embedding)
5. Enhance quadruple-level embedding with textual data
    * CMF (fuse multi-level contextual information into relation embedding)
    * ECOLA (tranformer-based fusion for text & quadruple)