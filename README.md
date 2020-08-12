# PoseTREID

### What is PoseTREID?

![alt text](https://raw.githubusercontent.com/rathaumons/PoseTREID/master/img/framework.png)

We propose a framework for real-time 2D multi-person tracking along with face re-identification specifically for distributed people interaction spaces such as malls or parks. Our proposed framework is able to efficiently track people and re-identify them later after the tracking is lost or after the absence of the people at some frames of the video.

More details? COMING SOON!

### Dataset

![alt text](https://raw.githubusercontent.com/rathaumons/PoseTREID/master/img/dataset_overview.jpg)

All videos were rendered in 16:9 ratio at a resolution of 1080p with our custom script. Afterwards, they were down-scaled to 720p to fit our real-time testing scenarios and more realistic real-life cameras with less good resolution. 

This dataset is specifically designed for **distributed people interaction spaces**.

### Results
By comparing to a state-of-the-art recent method [STAF](https://cmu-perceptual-computing-lab.github.io/spatio-temporal-affinity-fields/) on our dataset, the results of the proposed PoseTREID model were superior in almost every scenarios.

For **real-time video comparison**: [CLICK HERE!](https://drive.google.com/open?id=1WLGrRAdQPV-tA9B2OZPEwwMvFDVAymqX)

| Complexity | Camera Conf. | STAF | Tracking only | Full mode |
| :-------------: | :-------------: | :-------------: | :-------------: | :-------------: |
| Normal | Low | 85.28% | 85.35% | 97.13% |
| Normal | High | 85.05% | 100% | 96.85% |
| Hard | Low | 41.13% | 38.36% | 91.31% |
| Hard | Front | 38.39% | 38.36% | 89.00% |
| Hard | High | 59.70% | 56.02% | 89.93% |
| Hard | Surveillance | 86.22% | 85.96% | 40.71% |
