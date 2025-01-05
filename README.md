# Trajectory-Clustering-Paper-Summary
Summary of papers on Trajectory Clustering
## Content
- [Online Trajectory Clustering](#Online-Trajectory-Clustering)

## Online Trajectory Clustering

| Idx | Article | Venue | Date | Method | Link | Note | Baseline |
|:-------:|-------|:-------:|:-------:|:-------:|:-------:|-------|:-------:|
|1| Ocean: Online Clustering and Evolution Analysis for Dynamic Streaming Data | ICDE | 2024 | Ocean | [paper](https://ieeexplore.ieee.org/abstract/document/10598139) | - |
|2| An Efficient and Distributed Framework for Real-Time Trajectory Stream Clustering | TKDE | 2023 | - | [paper](https://ieeexplore.ieee.org/abstract/document/10239520) | - |`OCluST`|
|3| Towards Adaptive Continuous Trajectory Clustering Over a Distributed Web Data Stream | Journal of Web Engineering | 2023 | ACTOR | [paper](https://ieeexplore.ieee.org/abstract/document/10261474) | - |
|4| Adaptive Trajectory Data Stream Clustering | International Conference on Computer & Communication Technologies (IC3T) | 2023 | - | [paper](https://link.springer.com/chapter/10.1007/978-981-99-9707-7_23) | - |
|5| Lunatory: A Real-Time Distributed Trajectory Clustering Framework for Web Big Data | International Conference on Web Engineering (ICWE) | 2022 | - | [paper](https://link.springer.com/chapter/10.1007/978-3-031-09917-5_15) | - |
|6| Evolutionary Clustering of Streaming Trajectories | preprint | 2021 | ECO | [paper](https://arxiv.org/abs/2109.11609) | - |
|7| Contrastive Clustering | AAAI | 2021 | CC | [paper](https://arxiv.org/abs/2009.09687) ,[code](https://github.com/Yunfan-Li/Contrastive-Clustering) | An online clutering method |
|8| Online real-time trajectory analysis based on adaptive time interval clustering algorithm | Big Data Mining and Analytics | 2020 | - | [paper](https://ieeexplore.ieee.org/abstract/document/9007874) | - |
|9| Online clustering of streaming trajectories | Frontiers of Computer Science | 2018 | OCluST | [paper](https://link.springer.com/article/10.1007/s11704-017-6325-0) | The author is the same as that of `TSCluWin`, and the method is similar to it. It includes a micro-clustering component for clustering and summarizing the latest trajectory segments at each time point, as well as a macro-clustering component for constructing macro-clusters based on micro-clusters within a specified time window. Although OCluST performs well in clustering streaming trajectory data, it relies on the sliding window model, which may be sensitive to the choice of window size, affecting the quality of clustering results. Additionally, it may face computational resource bottlenecks under high-frequency data streams.|
|10| Semantic-Aware Clustering-based Approach of Trajectory Data Stream Mining | ICNC | 2018 | - | [paper](https://ieeexplore.ieee.org/abstract/document/8390371) |
|11| Spatio-Temporal Vessel Trajectory Clustering Based on Data Mapping and Density | IEEE Access | 2018 | - | [paper](https://ieeexplore.ieee.org/abstract/document/8443320) |
|12| TSCluWin: Trajectory Stream Clustering over Sliding Window | DASFAA | 2016 | TSCluWin | [paper](https://link.springer.com/chapter/10.1007/978-3-319-32049-6_9) |
|13| Online clustering of trajectory data stream | MDM | 2016 | - | [paper](https://ieeexplore.ieee.org/abstract/document/7517785/) | It processes real-time trajectory data using sliding window technology. This method maintains summary information of trajectory data within the sliding window to achieve online clustering of trajectory data streams. However, the choice of window size has a significant impact on clustering results—a window that is too small may fail to capture patterns adequately, while a window that is too large may increase computational overhead. Moreover, this method may have limitations in handling concept drift and the dynamic changes of trajectory data. |
|14| CUTiS: optimized online ClUstering of Trajectory data Stream | IDEAS | 2016 | CUTiS | [paper](https://dl.acm.org/doi/abs/10.1145/2938503.2938516) | 
|15| An Incremental DPMM-Based Method for Trajectory Clustering, Modeling, and Retrieval | TPAMI | 2013 | - | [paper](https://ieeexplore.ieee.org/abstract/document/6482546) |
|16| Continuous clustering trajectory stream of moving objects | China Communications | 2013 | - | [paper](https://ieeexplore.ieee.org/abstract/document/6623510) |
|17| Online clustering for trajectory data stream of moving objects | Computer Science and Information Systems | 2013 | CTraStream | [paper](https://doiserbia.nb.rs/img/doi/1820-0214/2013/1820-02141300049Y.pdf) | 
|18| Incremental Clustering for Trajectories | DASFAA | 2010 | TCMM | [paper](https://link.springer.com/chapter/10.1007/978-3-642-12098-5_3) | It is divided into two stages: online micro-cluster maintenance and offline macro-cluster creation. In the online stage, newly arriving trajectories are simplified into directed line segments and assigned to existing micro-clusters or used to create new micro-clusters based on similarity, capturing clustering features of trajectory segments. In the offline stage, the micro-clusters are further clustered to form macro-clusters, representing higher-level trajectory patterns.
