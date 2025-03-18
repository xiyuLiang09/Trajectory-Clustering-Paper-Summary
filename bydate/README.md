# Trajectory-Clustering-Paper-Summary
Summary of papers on Trajectory Clustering
## Content
- [Online Trajectory Clustering](#Online-Trajectory-Clustering)

## Online Trajectory Clustering

### 2024
- **"Ocean: Online Clustering and Evolution Analysis for Dynamic Streaming Data"**, ICDE'2024, `Ocean`, [paper](https://ieeexplore.ieee.org/abstract/document/10598139)

### 2023
- **"An Efficient and Distributed Framework for Real-Time Trajectory Stream Clustering"**, TKDE'2023, [paper](https://ieeexplore.ieee.org/abstract/document/10239520)
    > Baseline: `OCluST`
- **"Towards Adaptive Continuous Trajectory Clustering Over a Distributed Web Data Stream"**, Journal of Web Engineering 2023, `ACTOR`, [paper](https://ieeexplore.ieee.org/abstract/document/10261474)
- **"Adaptive Trajectory Data Stream Clustering"**, IC3T'2023, [paper](https://link.springer.com/chapter/10.1007/978-981-99-9707-7_23)

### 2022
- **"Lunatory: A Real-Time Distributed Trajectory Clustering Framework for Web Big Data"**, ICWE'2022, [paper](https://link.springer.com/chapter/10.1007/978-3-031-09917-5_15)
- **"Evolutionary Clustering of Moving Objects"**, ICDE'2022, [paper](https://ieeexplore.ieee.org/abstract/document/9835597)

### 2021
- **"Evolutionary Clustering of Streaming Trajectories"**, preprint, `ECO`, [paper](https://arxiv.org/abs/2109.11609)

### 2020
- **"Online real-time trajectory analysis based on adaptive time interval clustering algorithm"**, Big Data Mining and Analytics, [paper](https://ieeexplore.ieee.org/abstract/document/9007874)

### 2018
- **"Online clustering of streaming trajectories"**, Frontiers of Computer Science, `OCluST`,[paper](https://link.springer.com/article/10.1007/s11704-017-6325-0)
    > The method is similar to `TSCluWin`. It includes a micro-clustering component for clustering and summarizing the latest trajectory segments at each time point, as well as a macro-clustering component for constructing macro-clusters based on micro-clusters within a specified time window. Although OCluST performs well in clustering streaming trajectory data, it relies on the sliding window model, which may be sensitive to the choice of window size, affecting the quality of clustering results. Additionally, it may face computational resource bottlenecks under high-frequency data streams.