# Dexterous Manipulation

정밀 팔/손 제어 정책 - Advanced arm and hand manipulation policies

---

## ACE: A Cross-Platform Visual-Exoskeletons System for Low-Cost Dexterous Teleoperation

**Authors**: Shiqi Yang, Minghuan Liu, Yuzhe Qin, Runyu Ding, Jialong Li, Xuxin Cheng, Ruihan Yang, Sha Yi, Xiaolong Wang

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2408.11805)
- 🌐 [Project Page](https://ace-teleop.github.io/)
- 💻 GitHub: TBA

### 요약 (Summary)

**English**: ACE is a cross-platform visual-exoskeleton system designed for low-cost dexterous teleoperation. The system utilizes a hand-facing camera to capture 3D hand poses and an exoskeleton mounted on a portable base, enabling accurate real-time capture of both finger and wrist poses. ACE can generalize to humanoid hands, arm-hands, arm-gripper, and quadruped-gripper systems with high-precision teleoperation, making it ideal for collecting large-scale manipulation data across different platforms.

**한글**: ACE는 저비용 정밀 원격조작을 위해 설계된 크로스 플랫폼 비주얼-엑소스켈레톤 시스템입니다. 시스템은 손을 향한 카메라를 사용하여 3D 손 포즈를 캡처하고 휴대용 베이스에 장착된 엑소스켈레톤을 통해 손가락과 손목 포즈를 정확하게 실시간으로 캡처합니다. ACE는 휴머노이드 손, 팔-손, 팔-그리퍼, 사족보행 로봇-그리퍼 시스템에 고정밀 원격조작으로 범용적으로 적용 가능하며, 다양한 플랫폼에서 대규모 조작 데이터를 수집하는 데 이상적입니다.

### Key Features
- Cross-platform compatibility (humanoid hands, grippers, quadrupeds)
- Low-cost design (~$1,000-2,000)
- 3D hand pose estimation from RGB camera
- Portable exoskeleton system
- High-precision finger and wrist tracking
- Real-time teleoperation capabilities
- Scalable data collection

---

## MaskedManipulator: Versatile Whole-Body Manipulation

**Authors**: Chen Tessler, Yifeng Jiang, Erwin Coumans, Zhengyi Luo, Gal Chechik, Xue Bin Peng

**Conference**: SA Conference Papers '25, Hong Kong

**Links**:
- 📄 arXiv: TBA
- 🌐 Project Page: TBA

### 요약 (Summary)

**English**: MaskedManipulator presents a versatile whole-body manipulation framework using masked motion learning. Unlike prior methods focused on detailed motion tracking, trajectory following, or teleoperation, this framework enables users to specify versatile high-level objectives such as target object poses or body poses. The system introduces a generative control policy distilled from a tracking controller trained on large-scale human motion capture data. This two-stage learning process allows the system to perform complex interaction behaviors while providing intuitive user control over both character and object motions.

**한글**: MaskedManipulator는 마스크된 모션 학습을 사용한 다목적 전신 조작 프레임워크를 제시합니다. 상세한 모션 추적, 궤적 추종 또는 원격조작에 초점을 맞춘 이전 방법들과 달리, 이 프레임워크는 사용자가 목표 물체 포즈나 신체 포즈와 같은 다재다능한 고수준 목표를 지정할 수 있게 합니다. 시스템은 대규모 인간 모션 캡처 데이터로 훈련된 추적 컨트롤러로부터 증류된 생성 제어 정책을 도입합니다. 이 2단계 학습 프로세스는 시스템이 캐릭터와 물체 동작 모두에 대한 직관적인 사용자 제어를 제공하면서 복잡한 상호작용 행동을 수행할 수 있게 합니다.

### Key Features
- Masked motion learning approach
- High-level objective specification
- Generative control policy
- Two-stage distillation learning
- Versatile manipulation capabilities
- GRAB dataset training
- Complex human-object interactions
- Goal-directed manipulation behaviors

---

## DeepMimic: Example-Guided Deep Reinforcement Learning of Physics-Based Character Skills

**Authors**: Xue Bin Peng, Pieter Abbeel, Sergey Levine, Michiel van de Panne

**Conference**: ACM Trans. Graph.

**Links**:
- 📄 arXiv: TBA
- 🌐 Project Page: TBA

### 요약 (Summary)

**English**: DeepMimic presents a data-driven approach to physics-based character animation using deep reinforcement learning. The system learns to imitate reference motion clips through RL, enabling characters to perform a wide variety of challenging skills including locomotion, acrobatics, and martial arts. The framework uses example demonstrations to guide the learning process, resulting in physically plausible and responsive character control.

**한글**: DeepMimic은 심층 강화학습을 사용한 물리 기반 캐릭터 애니메이션에 대한 데이터 기반 접근법을 제시합니다. 시스템은 RL을 통해 참조 모션 클립을 모방하는 방법을 학습하여 캐릭터가 보행, 곡예, 무술을 포함한 다양한 도전적인 기술을 수행할 수 있게 합니다. 프레임워크는 예시 시연을 사용하여 학습 프로세스를 안내하며, 물리적으로 타당하고 반응성 있는 캐릭터 제어를 결과로 냅니다.

### Key Features
- Example-guided reinforcement learning
- Physics-based character control
- Diverse skill learning (locomotion, acrobatics, martial arts)
- Motion imitation framework
- Deep RL for character animation
- Reference motion tracking
- Responsive and plausible control

---

## Unleashing Humanoid Reaching Potential via Real-world-Ready Skill Space

**Authors**: Zhikai Zhang, Chao Chen, Han Xue, Jilong Wang, Sikai Liang, Yun Liu, Zongzhang Zhang, He Wang, Li Yi

**Year**: 2025

**Links**:
- 📄 arXiv: TBA
- 🌐 Project Page: TBA

### 요약 (Summary)

**English**: This work presents a framework for unleashing humanoid reaching potential through a real-world-ready skill space. The system enables humanoids to perform diverse reaching and manipulation tasks with high precision and adaptability. By learning in a structured skill space, the humanoid can generalize to various reaching scenarios and object interactions.

**한글**: 이 연구는 실제 세계 준비가 된 기술 공간을 통해 휴머노이드의 도달 잠재력을 발휘하는 프레임워크를 제시합니다. 시스템은 휴머노이드가 높은 정밀도와 적응성으로 다양한 도달 및 조작 작업을 수행할 수 있게 합니다. 구조화된 기술 공간에서 학습함으로써 휴머노이드는 다양한 도달 시나리오와 물체 상호작용에 일반화할 수 있습니다.

### Key Features
- Real-world-ready skill space
- Diverse reaching capabilities
- High-precision manipulation
- Adaptive task execution
- Structured skill learning
- Generalization to various scenarios

---

[Back to Main README](../README.md)
