# FGO-ILNS
FGO-ILNS: Multi-Sensor Integrated Navigation System Based on Factor Graph Optimization for Autonomous Underwater Vehicle

Localization is an essential issue for autonomous
underwater vehicles (AUVs) in the Internet of Underwater Things
(IoUT). Coupling the strapdown inertial navigation system (SINS)
with the long baseline location system (LBL) is an effective way to
solve the underwater positioning of AUVs. However, underwater
multi-sensor integrated navigation systems face challenges such as
heterogeneous frequency and dynamic availability of sensors.
Traditional underwater multi-sensor fusion algorithms often use
filter-based methods, which suffer from low accuracy and
robustness when sensors become unavailable. The factor graph
method can enable multi-sensor plug-and-play and fusion of data
with different sampling frequencies. Therefore, we propose a
factor graph optimization-based SINS/LBL tightly coupled
navigation system (FGO-ILNS), which tightly couples SINS and
LBL. Sensors such as Doppler velocity log (DVL), magnetic
compass pilot (MCP), pressure sensor (PS), and global navigation
satellite system (GNSS) can be easily extended to satisfy different
navigation scenarios. We establish a floating LBL slant range
difference factor node model, which is tightly coupled with sensor
factors such as SINS to achieve unification of global position above
and below water. Moreover, we utilize the marginalization method
to reduce the computational load of factor graph optimization.
Simulation and public KAIST dataset experiments have verified
that, compared to traditional filter-based algorithms like the
extended Kalman filter (EKF) and federal Kalman filter (FKF), as
well as the state-of-the-art optimization-based algorithm ORBSLAM3, our proposed FGO-ILNS leads in accuracy and
robustness. This system provides a reference scheme for global
large-scale underwater positioning of AUVs.
![FGOILNS](https://github.com/JiangboSong251/FGO-ILNS/blob/main/FGOILNS.png)
