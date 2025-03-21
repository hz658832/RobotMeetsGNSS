+++
title = "Motivation and Goal"
+++


# Motivation

Robot navigation in outdoor environments typically requires globally consistent state estimation for effective planning and coordination. Traditional Simultaneous Localization and Mapping (SLAM) approaches using local sensors (e.g., LiDARs, cameras) are often inefficient and unreliable due to scarce loop-closure constraints and sensor degradation in large-scale outdoor conditions. In this context, the Global Navigation Satellite System (GNSS) offers an effective, low-cost complementary sensing modality for robotic applications.


| ![](trend.png) | 
|:--:| 
| *Figure 1: Analysis of GNSS-enabled research publications from 2018 to 2025 across major publications and venues in the robotics community (IEEE RAS, RSS, IJRR, Robotica, J-FR). The key word “fusion” categorizes research focusing on state estimation using GNSS measurements, while papers under “solution” apply GNSS solutions to downstream tasks, e.g., HD map generation* |

Over the years, GNSS has been widely recognized within the robotics community, with numerous studies demonstrating its crucial role in achieving globally consistent state estimation and long-term navigation (see Figure 1a and 1c). However, significant gaps remain between the GNSS and robotics research communities, as advanced breakthroughs are often not effectively communicated. This is particularly evident in robotic applications where GNSS performance degrades due to signal interference (e.g., multipath, non-line-of-sight) in complex environments. Figure 1b highlights how robotics research mainly employs GNSS at the application level, leaving key challenges in robustness, integrity, and long-term autonomy underexplored.

Meanwhile, recent GNSS advances address these challenges, often sharing theoretical foundations with robotics problems like SLAM. Bridging these fields offers significant potential to enhance outdoor robot localization.

# Goal
This workshop aims to unite cutting-edge research from both communities, fostering high-level exchanges on robotic applications leveraging GNSS and similar sensing modalities for accurate and reliable state estimation. Given that the GNSS and robotics communities face similar challenges in algorithm development—such as robust error modeling, hyper-parameter tuning, and certifiable solvers—the workshop seeks to create a platform that brings together invited experts, industry representatives, and particularly young researchers to collaborate on these shared issues and accelerate progress in both fields. In addition, we expect to share ideas and insights that enable the transfer of GNSS research know-how to other ranging sensors. 
