+++
title = "Motivation and Goal"
+++


# Motivation

<p class="uk-text-custom uk-text-justify">
Simultaneous Localization and Mapping (SLAM) using robot-centric sensors such as LiDAR and cameras
has been shaped by decades of intensive research and has become the cornerstone of robotic navigation.
However, SLAM approaches often struggle in large-scale outdoor environments due to limited loop-closure
opportunities and sensor degradation. In contrast, radio-based ranging sensors can provide globally consistent
observations, offering a promising complement to traditional SLAM.
</p>

<figure style="text-align:left;">
  <img src="trend.png" alt="GNSS and UWB trend" width="1200">
  <figcaption style="color:blue; text-align:left; font-style:italic;">
    Figure 1: Analysis of GNSS and UWB-enabled research publications from 2018 to 2025 across major publications and venues in the robotics community (IEEE T-RO, IEEE T-FR, IEEE T-ASE, IEEE RA-L, IEEE ICRA, IEEE IROS, IEEE CASE, RSS, IJRR, Robotica). Publications labeled tightly coupled fusion focus on state estimation using range measurements, while loosely coupled fusion refers to approaches that apply GNSS solutions to downstream tasks. The category robustness covers studies on noise modeling, fault detection, and exclusion. Although publication counts indicate a growing interest in this research area within the robotics community, the robustness of range-based observations remains underexplored.
  </figcaption>
</figure>

<p class="uk-text-custom uk-text-justify">
Over the years, radio-based ranging sensors, such as GNSS and Ultra-Wideband (UWB), have been widely
recognized within the robotics community, with numerous studies demonstrating their crucial role in achieving
globally consistent state estimation and long-term navigation. Figure 1a illustrates the growing research interest in leveraging these sensors for both indoor and field robotic applications, as evidenced by the steady
increase in publications across major robotics venues. Today, ranging sensors and established ranging
systems (e.g., GNSS) are capable of providing efficient and flexible state observations with high availability
across wide geographic areas and scalability in real-world robotic operations, making them indispensable
toward cost-effective and sustainable robotic autonomy.
</p>

<p class="uk-text-custom uk-text-justify">
Recent works on topics such as equivariant filters, noise model identification, and certifiable optimization
support our observation of the significant impact and potential of ranging sensors in robotic research.
However, as illustrated in Figure 1b, research areas such as robustness remain comparatively
underexplored.
</p>


# Goal
<p class="uk-text-custom uk-text-justify">
This workshop aims to <b>bring together cutting-edge research from both communities and foster high-level discussions on robotic applications that leverage GNSS and related sensing modalities for accurate and reliable state estimation</b>. Since the GNSS/Ranging and robotics communities face similar challenges in algorithm development—such as robust error modeling, hyperparameter tuning, and certifiable solvers—the workshop will provide a platform for invited experts, industry representatives, and especially young researchers to collaborate on these shared issues and accelerate progress in both fields. Furthermore, we expect the exchange of ideas and insights to facilitate the transfer of GNSS and ranging research know-how to other sensor technologies.
</p>