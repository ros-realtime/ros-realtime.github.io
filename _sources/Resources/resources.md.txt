# Resources

This document contains a compilation of ROS and real-time related documents, articles, and discussions.


## ROS 2 design

- [Introduction to Real-time Systems](http://design.ros2.org/articles/realtime_background.html)
- [Proposal for Implementation of Real-time Systems in ROS 2](https://design.ros2.org/articles/realtime_proposal.html)


## Tutorials / Guides

- [Real-time programming in ROS 2](https://docs.ros.org/en/rolling/Tutorials/Real-Time-Programming.html)
- [Building real-time Linux for ROS 2](https://docs.ros.org/en/rolling/Tutorials/Building-Realtime-rt_preempt-kernel-for-ROS-2.html)
- [Real-time programming with Linux (2022)](https://shuhaowu.com/blogseries.html#rt-linux-programming)

## ROS Enhancement Proposals (REPs)

- [REP-2014: Benchmarking performance in ROS 2](https://ros.org/reps/rep-2014.html)
- [DRAFT-REP-2017: Thread attributes configuration support in rcl](https://github.com/ros-infrastructure/rep/pull/385)

## ROSCon

### ROSCon 2015

- Real-time control in ROS and ROS 2.0 [Slides](https://roscon.ros.org/2015/presentations/RealtimeROS2.pdf) [Video](https://vimeo.com/142621778)

### ROSCon 2016

- Evaluating the resilience of ROS2 communication layer [Slides](https://roscon.ros.org/2016/presentations/rafal.kozik-ros2evaluation.pdf) [Video](https://vimeo.com/187705229)

### ROSCon 2017

- Determinism in ROS [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20Determinism%20in%20ROS.pdf) [Video](https://vimeo.com/236186712)

### ROSCon 2018

- Performance Test - A Tool for Communication Middleware Performance Measuring [Slides](https://roscon.ros.org/2018/presentations/ROSCon2018_MiddlewarePerformanceTesting.pdf) [Video](https://vimeo.com/293257342)
- ROS 2 on Autonomous Vehicles [Slides](https://roscon.ros.org/2018/presentations/ROSCon2018_ROS2onAutonomousDrivingVehicles.pdf) [Video](https://vimeo.com/292695688)
- Lessons learned building a self-driving car on ROS [Slides](https://roscon.ros.org/2018/presentations/ROSCon2018_LessonsLearnedSelfDriving.pdf) [Video](https://vimeo.com/292693011)
- Mixed Real-Time Criticality with ROS2 - the Callback-group-level Executor [slides](https://roscon.ros.org/2018/presentations/ROSCon2018_Lightning1_4.pdf) [video](https://vimeo.com/292707644)

### ROSCon 2019

- ROS 2 ON VXWORKS [slides](https://roscon.ros.org/2019/talks/roscon2019_ros2onvxworks.pdf) [video](https://vimeo.com/378682144)
- Concurrency in ROS 1 and 2: from AsyncSpinner to MultithreadedExecutor [slides](https://roscon.ros.org/2019/talks/roscon2019_concurrency.pdf) [video](https://vimeo.com/379127709)
- ROS2 Real-Time Behavior: Static Memory Allocation [video](https://vimeo.com/379127767)
- [**Workshop**: Doing Real-Time with ROS 2: Capabilities and Challenges](https://www.apex.ai/roscon2019)

### ROSConJP 2019

- Real-time control in RedHawk and ROS 2.0 [slides](https://roscon.ros.org/jp/2019/presentations/ROSCon_JP_2019_presentation_14.pdf) [video](https://vimeopro.com/osrfoundation/roscon-jp-2019/video/370248812)

### ROSWorld 2020

- [Boost pool allocation](https://vimeo.com/480521240)

### ROSWorld 2021

- [Apex.OS Cert: Taking ROS 2 from prototype into production](https://vimeo.com/649645295/67e0a6569f)
- [**Workshop**: ROS 2 Executor: How to make it efficient,real-time and deterministic?](https://www.apex.ai/roscon-21)

### ROSCon 2022

- System Modes - model-based run-time state management of large systems [Slides](http://download.ros.org/downloads/roscon/2022/System%20Modes%20-%20model-based%20run-time%20state%20management%20of%20large%20systems.pdf) [Video](https://vimeo.com/767165876)
- Chain-Aware ROS Evaluation Tool [Slides](http://download.ros.org/downloads/roscon/2022/Chain-Aware%20ROS%20Evaluation%20Tool%20(CARET).pdf) [Video](https://vimeo.com/showcase/9954564/video/767150288)

### ROSCon 2023

- [**Workshop**: Real-Time Programming with ROS 2](https://ros-realtime.github.io/roscon-2023-realtime-workshop/)
- Real-time Data-flow extension for ROS 2 [Slides](https://roscon.ros.org/2023/talks/Real-time_Data-flow_extension_for_ROS_2.pdf) [Video](https://vimeo.com/879001546/54514e92c0)
- Using Reference System to evaluate features and performance in a standardized and repeatable way [Slides](https://roscon.ros.org/2023/talks/Using_Reference_System_to_evaluate_features_and_performance_in_a_standardized_and_repeatable_way.pdf) [Video](https://vimeo.com/881734034/8f6282d0ee)

### ROSCon 2024

- Executors in ROS 2 [Slides](https://roscon.ros.org/2024/talks/Executors_in_ROS_2.pdf) [Video](https://vimeo.com/1024970052)
- The Multithreaded Events Executor [Slides](https://roscon.ros.org/2024/talks/The_Multithreaded_Events_Executor.pdf) [Video](https://vimeo.com/1024972104)
- Real-time ROS 2 applications made easy with cactus-rt [Slides](https://roscon.ros.org/2024/talks/Real-time_ROS_2_applications_made_easy_with_cactus-rt.pdf) [Video](https://vimeo.com/1024971584)


## Articles

- [Exploring the performance of ROS2](https://www.semanticscholar.org/paper/Exploring-the-performance-of-ROS2-Maruyama-Kato/8ea66e5c80705b09957caf2cf78b8041e7362a44)
- [Towards a distributed and real-time framework for robots: Evaluation of ROS 2.0 communications for real-time robotic applications](https://arxiv.org/pdf/1809.02595.pdf)
- [Response-Time Analysis of ROS 2 Processing Chains under Reservation-Based Scheduling](https://t-blass.de/papers/response-time-analysis-of-ros2.pdf)
- [Latency Overhead of ROS2 for Modular Time-Critical Systems](https://arxiv.org/pdf/2101.02074.pdf)
- [Exploring Real-Time Executor on ROS 2](https://ieeexplore.ieee.org/document/9301530)
- [Distributed and Synchronized Setup towards Real-Time Robotic Control using ROS2 on Linux](https://ieeexplore.ieee.org/document/9217010)
- [Jan Staschulat, Ingo Lütkebohle, Ralph Lange. The rclc Executor: Domain-specific deterministic scheduling mechanisms for ROS applications on microcontrollers, EMSOFT 2020.](https://ieeexplore.ieee.org/document/9244014)
- [Jan Staschulat, Ralph Lange, Dakshina Narahari Dasari. Budget-based real-time Executor for Micro-ROS. CoRR arXiv:2105.05590, May 2021](https://arxiv.org/abs/2105.05590)
- [L. Puck et al. Distributed and Synchronized Setup towards Real-Time Robotic Control using ROS2 on Linux](https://ieeexplore.ieee.org/document/9217010)
- [Christophe Bédard, Ingo Lütkebohle, Michel Dagenais. ros2_tracing: Multipurpose Low-Overhead Framework for Real-Time Tracing of ROS 2.](https://arxiv.org/pdf/2201.00393.pdf)
- [Christophe Bédard, Pierre-Yves Lajoie, Giovanni Beltrame, Michel Dagenais. Message Flow Analysis with Complex Causal Links for Distributed ROS 2 Systems](https://arxiv.org/pdf/2204.10208.pdf)