# Whole-Body Oriented Teleoperation

전신 협응 원격조작 시스템 - Coordinated full-body control systems

---

## CLONE: Closed-Loop Whole-Body Humanoid Teleoperation for Long-Horizon Tasks

**Authors**: Yixuan Li, Yutang Lin, Jieming Cui, Tengyu Liu, Wei Liang, Yixin Zhu, Siyuan Huang

**Year**: 2025

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2506.08931)
- 🌐 [Project](https://humanoid-clone.github.io/)
- 💻 [GitHub](https://github.com/humanoid-clone/CLONE/)

### 요약 (Summary)

 CLONE is a closed-loop whole-body teleoperation system that achieves comprehensive robot control using only a VR headset. It employs a Mixture-of-Experts (MoE) architecture that learns diverse motion skills while a LiDAR-based error correction mechanism prevents the accumulation of positional drift. CLONE enables unprecedented whole-body teleoperation fidelity, maintaining minimal positional drift (5.1cm mean error over 8.9m) over long-range trajectories using only head and hand tracking from an MR headset.

 CLONE은 VR 헤드셋만을 사용하여 포괄적인 로봇 제어를 달성하는 폐루프 전신 원격조작 시스템입니다. 다양한 모션 기술을 학습하는 Mixture-of-Experts (MoE) 아키텍처를 채용하며, LiDAR 기반 오류 보정 메커니즘이 위치 드리프트 축적을 방지합니다. CLONE은 MR 헤드셋의 머리와 손 추적만으로 장거리 궤적에서 최소한의 위치 드리프트(8.9m에서 5.1cm 평균 오류)를 유지하며 전례 없는 전신 원격조작 정확도를 가능하게 합니다.

### Key Features
- MoE-based teleoperation framework
- Closed-loop error correction with LiDAR odometry
- Minimal hardware requirements (only MR headset)
- Long-horizon task capabilities (15m+ trajectories)
- Real-time coordination of upper and lower body
- CLONED dataset with augmented motion data

---

## TWIST: Teleoperated Whole-Body Imitation System

**Authors**: Yanjie Ze, Zixuan Chen, João Pedro Araújo, Zi-ang Cao, Xue Bin Peng, Jiajun Wu, C. Karen Liu

**Year**: 2025

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2505.02833)
- 🌐 [Project](https://yanjieze.com/TWIST/)
- 💻 [GitHub](https://github.com/YanjieZe/TWIST)

### 요약 (Summary)

 TWIST presents a system for humanoid teleoperation through whole-body motion imitation. The system generates reference motion clips by retargeting human motion capture data to the humanoid robot, then develops a robust, adaptive, and responsive whole-body controller using a combination of reinforcement learning and behavior cloning (RL+BC). Through systematic analysis, TWIST demonstrates how incorporating privileged future motion frames and real-world motion capture data improves tracking accuracy. The system enables real-world humanoid robots to achieve unprecedented, versatile, and coordinated whole-body motor skills spanning whole-body manipulation, legged manipulation, locomotion, and expressive movement using a single unified neural network controller.

 TWIST는 전신 동작 모방을 통한 휴머노이드 원격조작 시스템을 제시합니다. 시스템은 인간 모션 캡처 데이터를 휴머노이드 로봇에 리타게팅하여 참조 모션 클립을 생성한 다음, 강화학습과 행동 복제(RL+BC)의 조합을 사용하여 견고하고 적응적이며 반응성 있는 전신 컨트롤러를 개발합니다. 체계적인 분석을 통해 TWIST는 특권적 미래 모션 프레임과 실제 모션 캡처 데이터를 통합하는 것이 추적 정확도를 향상시키는 방법을 보여줍니다. 시스템은 단일 통합 신경망 컨트롤러를 사용하여 전신 조작, 다리 조작, 이동, 표현적 움직임을 포괄하는 전례 없이 다재다능하고 협응된 전신 운동 기술을 실제 휴머노이드 로봇이 달성할 수 있게 합니다.

### Key Features
- RL+BC hybrid training approach
- Whole-body motion retargeting from human MoCap
- Privileged future motion frame incorporation
- Versatile motor skills (manipulation, locomotion, expressive movement)
- Single unified neural network controller
- Real-time teleoperation capabilities

---

## Mobile-TeleVision: Predictive Motion Priors for Humanoid Whole-Body Control

**Authors**: Chenhao Lu, Xuxin Cheng, Jialong Li, Shiqi Yang, Mazeyu Ji, Chengjing Yuan, Ge Yang, Sha Yi, Xiaolong Wang

**Conference**: ICRA 2025

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2412.07773)
- 🌐 [Project](https://mobile-tv.github.io/)
- 💻 [GitHub](https://github.com/OpenTeleVision/TeleVision)

### 요약 (Summary)

 Mobile-TeleVision proposes decoupling upper-body control from locomotion, using inverse kinematics (IK) and motion retargeting for precise manipulation, while RL focuses on robust lower-body locomotion. The key innovation is PMP (Predictive Motion Priors), trained with Conditional Variational Autoencoder (CVAE) to effectively represent upper-body motions. The locomotion policy is trained conditioned on this upper-body motion representation, ensuring that the system remains robust with both manipulation and locomotion. The system significantly outperforms RL-based whole-body control in precise manipulation tasks.

 Mobile-TeleVision은 상체 제어를 이동으로부터 분리하여, 정밀 조작을 위해 역운동학(IK)과 모션 리타게팅을 사용하고, RL은 견고한 하체 이동에 집중하도록 제안합니다. 핵심 혁신은 조건부 변분 오토인코더(CVAE)로 훈련되어 상체 동작을 효과적으로 표현하는 PMP(예측 모션 사전)입니다. 이동 정책은 이 상체 동작 표현에 조건화되어 훈련되므로, 시스템이 조작과 이동 모두에서 견고하게 유지됩니다. 시스템은 정밀 조작 작업에서 RL 기반 전신 제어를 크게 능가합니다.

### Key Features
- Decoupled upper-body and lower-body control
- Predictive Motion Priors (PMP) with CVAE
- IK-based precise upper-body manipulation
- RL-based robust lower-body locomotion
- Superior manipulation precision vs. end-to-end RL
- Real-world deployment on Fourier GR1 and Unitree H1

---

## HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit

**Authors**: Qingwei Ben, Feiyu Jia, Jia Zeng, Junting Dong, Dahua Lin, Jiangmiao Pang

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2502.13013)
- 🌐 [Project](https://homietele.github.io/)
- 💻 [GitHub](https://github.com/InternRobotics/OpenHomie)

### 요약 (Summary)

**English**: HOMIE presents a humanoid loco-manipulation system using an isomorphic exoskeleton cockpit for teleoperation. The system enables intuitive whole-body control through a human-worn exoskeleton that mirrors the robot's morphology.

**한글**: HOMIE는 원격조작을 위한 동형 엑소스켈레톤 조종석을 사용하는 휴머노이드 로코-매니퓰레이션 시스템을 제시합니다. 이 시스템은 로봇의 형태를 반영하는 인간이 착용하는 엑소스켈레톤을 통해 직관적인 전신 제어를 가능하게 합니다.

### Key Features
- Isomorphic exoskeleton design
- Whole-body loco-manipulation
- Intuitive teleoperation interface
- Real-time motion capture and control

---

## OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning

**Authors**: Tairan He, Zhengyi Luo, Xialin He, Wenli Xiao, Chong Zhang, Weinan Zhang, Kris Kitani, Changliu Liu, Guanya Shi

**Conference**: CoRL 2024

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2406.08858)
- 🌐 [Project](https://omni.human2humanoid.com/)
- 💻 [GitHub](https://github.com/LeCAR-Lab/human2humanoid)

### 요약 (Summary)

 OmniH2O presents a learning-based system for whole-body humanoid teleoperation and autonomy. Using kinematic pose as a universal control interface, OmniH2O enables various ways for a human to control a full-sized humanoid with dexterous hands, including real-time teleoperation through VR headset, verbal instruction, and RGB camera. It also enables full autonomy by learning from teleoperated demonstrations or integrating with frontier models such as GPT-4. The system demonstrates versatility and dexterity in various real-world whole-body tasks such as playing multiple sports, moving and manipulating objects, and interacting with humans.

 OmniH2O는 전신 휴머노이드 원격조작 및 자율성을 위한 학습 기반 시스템을 제시합니다. 운동학적 포즈를 범용 제어 인터페이스로 사용하여, OmniH2O는 VR 헤드셋, 음성 명령, RGB 카메라를 통한 실시간 원격조작을 포함하여 인간이 정밀한 손을 가진 전신 크기 휴머노이드를 제어하는 다양한 방법을 가능하게 합니다. 또한 원격조작 시연으로부터 학습하거나 GPT-4와 같은 최첨단 모델과 통합하여 완전한 자율성을 가능하게 합니다. 시스템은 여러 스포츠 경기, 물체 이동 및 조작, 인간과의 상호작용 등 다양한 실제 전신 작업에서 다재다능함과 정밀함을 보여줍니다.

### Key Features
- Universal kinematic pose control interface
- Multiple teleoperation modalities (VR, voice, camera)
- GPT-4 integration for autonomy
- Dexterous hand control
- OmniH2O-6 dataset (6 everyday tasks)
- Robust sim-to-real transfer pipeline

---
## H2O: Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation

**Authors**: Tairan He, Zhengyi Luo, Wenli Xiao, Chong Zhang, Kris Kitani, Changliu Liu, Guanya Shi

**Conference**: IROS 2024

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2403.04436)
- 🌐 [Project](https://human2humanoid.com/)
- 💻 [GitHub](https://github.com/LeCAR-Lab/human2humanoid)

### 요약 (Summary)

 H2O presents a reinforcement learning (RL) based framework that enables real-time whole-body teleoperation of a full-sized humanoid robot with only an RGB camera. To create a large-scale retargeted motion dataset, the paper proposes a scalable "sim-to-data" process to filter and pick feasible motions using a privileged motion imitator. The trained policy successfully achieves teleoperation of dynamic whole-body motions in real-world scenarios, including walking, back jumping, kicking, turning, waving, pushing, and boxing. This is the first demonstration to achieve learning-based real-time whole-body humanoid teleoperation.

 H2O는 RGB 카메라만으로 전신 크기 휴머노이드 로봇의 실시간 전신 원격조작을 가능하게 하는 강화학습(RL) 기반 프레임워크를 제시합니다. 대규모 리타게팅된 모션 데이터셋을 생성하기 위해, 논문은 특권적 모션 모방자를 사용하여 실행 가능한 모션을 필터링하고 선택하는 확장 가능한 "시뮬레이션에서 데이터로" 프로세스를 제안합니다. 훈련된 정책은 걷기, 뒤로 점프하기, 차기, 돌기, 손 흔들기, 밀기, 복싱을 포함한 실제 시나리오에서 동적 전신 동작의 원격조작을 성공적으로 달성합니다. 이것은 학습 기반 실시간 전신 휴머노이드 원격조작을 달성한 첫 번째 시연입니다.

### Key Features
- First real-time whole-body teleoperation via learning
- RGB camera-only system
- "Sim-to-data" motion filtering process
- Dynamic motion capabilities (jumping, kicking, boxing)
- Zero-shot sim-to-real transfer
- AMASS dataset utilization

---
[Back to Main README](../README.md)
