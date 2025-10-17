# Acrobatic & Body Motion

고도로 동적인 전신 움직임 - Highly dynamic skills: kung-fu, balance, parkour

---

## GMT: General Motion Tracking for Humanoid Whole-Body Control

**Authors**: Zixuan Chen, Mazeyu Ji, Xuxin Cheng, Xuanbin Peng, Xue Bin Peng, Xiaolong Wang

**Year**: 2025

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2506.14770)
- 🌐 [Project Page](https://gmt-humanoid.github.io/)
- 💻 [GitHub](https://github.com/zixuan417/humanoid-general-motion-tracking)

### 요약 (Summary)

 GMT proposes a general and scalable motion-tracking framework that trains a single unified policy to enable humanoid robots to track diverse motions in the real world. GMT is built upon two core components: an Adaptive Sampling strategy and a Motion Mixture-of-Experts (MoE) architecture. The Adaptive Sampling automatically balances easy and difficult motions during training, while the MoE ensures better specialization of different regions of the motion manifold. GMT achieves state-of-the-art performance across a broad spectrum of motions using a unified general policy, including stretching, kicking, dancing, high kicking, kung-fu, boxing, running, side stepping, and squatting.

 GMT는 휴머노이드 로봇이 실제 세계에서 다양한 동작을 추적할 수 있도록 단일 통합 정책을 훈련하는 일반적이고 확장 가능한 모션 추적 프레임워크를 제안합니다. GMT는 두 가지 핵심 구성 요소인 적응형 샘플링 전략과 모션 Mixture-of-Experts (MoE) 아키텍처를 기반으로 합니다. 적응형 샘플링은 훈련 중 쉬운 동작과 어려운 동작의 균형을 자동으로 맞추고, MoE는 모션 매니폴드의 다른 영역에 대한 더 나은 전문화를 보장합니다. GMT는 스트레칭, 킥, 댄스, 하이 킥, 쿵푸, 복싱, 달리기, 측면 스텝, 스쿼트를 포함한 광범위한 동작 스펙트럼에 걸쳐 통합 일반 정책을 사용하여 최첨단 성능을 달성합니다.

### Key Features
- Unified general motion tracking policy
- Adaptive Sampling strategy for balanced training
- Motion Mixture-of-Experts (MoE) architecture
- State-of-the-art tracking performance
- Diverse motion capabilities (locomotion + acrobatics)
- Real-world deployment on Unitree G1
- Single policy for all motion types

---

## BeyondMimic: From Motion Tracking to Versatile Humanoid Control via Guided Diffusion

**Authors**: Qiayuan Liao, Takara E. Truong, Xiaoyu Huang, Guy Tevet, Koushil Sreenath, C. Karen Liu

**Year**: 2025

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2508.08241)
- 🌐 [Project Page](https://beyondmimic.github.io/)
- 💻 [GitHub](https://github.com/HybridRobotics/whole_body_tracking)

### 요약 (Summary)

 BeyondMimic presents a real-world framework to learn from human motions for versatile and naturalistic humanoid control via guided diffusion. The framework provides a motion tracking pipeline capable of challenging skills such as jumping spins, sprinting, and cartwheels with state-of-the-art motion quality. Moving beyond simply mimicking existing motions, BeyondMimic introduces a unified diffusion policy that enables zero-shot task-specific control at test time using simple cost functions. Deployed on hardware, BeyondMimic performs diverse tasks at test time, including waypoint navigation, joystick teleoperation, and obstacle avoidance, bridging sim-to-real motion tracking and flexible synthesis of human motion primitives for whole-body control.

 BeyondMimic은 가이드 확산을 통한 다재다능하고 자연스러운 휴머노이드 제어를 위해 인간 동작으로부터 학습하는 실제 세계 프레임워크를 제시합니다. 프레임워크는 최첨단 모션 품질로 점프 스핀, 전력 질주, 재주넘기와 같은 도전적인 기술이 가능한 모션 추적 파이프라인을 제공합니다. 기존 동작을 단순히 모방하는 것을 넘어, BeyondMimic은 간단한 비용 함수를 사용하여 테스트 시점에 제로샷 작업별 제어를 가능하게 하는 통합 확산 정책을 도입합니다. 하드웨어에 배치된 BeyondMimic은 경유지 네비게이션, 조이스틱 원격조작, 장애물 회피를 포함한 다양한 작업을 테스트 시점에 수행하여 전신 제어를 위한 실제-실제 모션 추적과 인간 모션 프리미티브의 유연한 합성을 연결합니다.

### Key Features
- Scalable motion tracking pipeline
- Guided diffusion for policy synthesis
- State-of-the-art motion quality
- Zero-shot task adaptation at test time
- Challenging skills (jumping spins, sprinting, cartwheels)
- Real-world deployment on Unitree G1
- Unified diffusion policy for diverse tasks
- Cost function-based guidance

---

## HuB: Learning Extreme Humanoid Balance

**Links**:
- 📄 [arXiv](https://arxiv.org/pdf/2505.07294)
- 🌐 [Project](https://hub-robot.github.io/)
- 💻 [GitHub] TBA

### 요약 (Summary)

 HuB focuses on learning extreme humanoid balance capabilities. The system enables humanoids to maintain balance in challenging scenarios, recover from perturbations, and perform dynamic balancing tasks that push the limits of stability.

 HuB는 극한의 휴머노이드 균형 능력 학습에 초점을 맞춥니다. 시스템은 휴머노이드가 도전적인 시나리오에서 균형을 유지하고, 섭동으로부터 회복하며, 안정성의 한계를 시험하는 동적 균형 작업을 수행할 수 있게 합니다.

### Key Features
- Extreme balance learning
- Perturbation recovery
- Dynamic balancing tasks
- Robust stability control
- Real-world deployment capabilities

---

## Embrace Collisions: Humanoid Shadowing for Deployable Contact-Agnostics Motions

**Authors**: Ziwen Zhuang, Hang Zhao

**Links**:
- 📄 [arXiv](https://arxiv.org/pdf/2502.01465)
- 🌐 [Project](https://project-instinct.github.io/)
- 💻 [GitHub] TBA

### 요약 (Summary)

 Embrace Collisions presents a humanoid shadowing approach for deployable contact-agnostic motions. Unlike traditional methods that avoid contact, this system learns to embrace and utilize collisions, enabling more natural and robust human-like movements including sitting, lying down, getting up from the ground, and transitioning between various postures.

 Embrace Collisions는 배치 가능한 접촉 무관 동작을 위한 휴머노이드 섀도잉 접근법을 제시합니다. 접촉을 피하는 전통적인 방법과 달리, 이 시스템은 충돌을 수용하고 활용하는 방법을 학습하여 앉기, 눕기, 바닥에서 일어나기, 다양한 자세 간 전환을 포함한 더 자연스럽고 견고한 인간과 같은 움직임을 가능하게 합니다.

### Key Features
- Contact-agnostic motion learning
- Collision-aware control
- Natural whole-body locomotion
- Posture transition capabilities
- Recovery from ground positions
- Robust real-world deployment

---
## KungfuBot: Physics-Based Humanoid Whole-Body Control for Learning Highly-Dynamic Skills

**Links**:
- 📄 [arXiv](https://arxiv.org/pdf/2506.12851)
- 🌐 [Project](https://kungfu-bot.github.io/)
- 💻 [GitHub](https://github.com/TeleHuman/PBHC) 

### 요약 (Summary)

 KungfuBot presents a physics-based humanoid whole-body control system for learning highly-dynamic skills such as kung-fu movements. The system leverages reinforcement learning to master complex, coordinated motions that require precise timing and balance.

: KungfuBot은 쿵푸 동작과 같은 고도로 동적인 기술을 학습하기 위한 물리 기반 휴머노이드 전신 제어 시스템을 제시합니다. 시스템은 정밀한 타이밍과 균형이 필요한 복잡하고 협응된 동작을 마스터하기 위해 강화학습을 활용합니다.

### Key Features
- Physics-based control for dynamic skills
- Kung-fu and martial arts movements
- Highly coordinated whole-body motions
- RL-based skill learning
- Real-time balance control

---

## Diffuse-CLoC: Guided Diffusion for Physics-based Character Look-ahead Control

**Authors**: Xiaoyu Huang, Takara Truong, Yunbo Zhang, Fangzhou Yu, Jean-Pierre Sleiman, Jessica Hodgins, K. Sreenath, Farbod Farshidian

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2503.11801)
- 🌐 [Project](https://diffusecloc.github.io/website/)
- 💻 [GitHub] TBA

### 요약 (Summary)

 Diffuse-CLoC introduces a guided diffusion approach for physics-based character control. The method combines diffusion models with look-ahead control to generate realistic and physically plausible character motions.

 Diffuse-CLoC은 물리 기반 캐릭터 제어를 위한 가이드 확산 접근법을 소개합니다. 이 방법은 확산 모델과 선행 제어를 결합하여 현실적이고 물리적으로 타당한 캐릭터 동작을 생성합니다.

### Key Features
- Guided diffusion for character control
- Physics-based motion generation
- Look-ahead control mechanism
- Realistic character animation

---

## Switch4EAI: Leveraging Console Game Platform for Benchmarking Robotic Athletics

**Authors**: Tianyu Li, Jeonghwan Kim, Wontaek Kim, Donghoon Baek, Seungeun Rho, Sehoon Ha

**Links**:
- 📄 [arXiv](https://www.arxiv.org/pdf/2508.13444)
- 🌐 Project Page: TBA

### 요약 (Summary)

 Switch4EAI leverages console game platforms for benchmarking robotic athletics. The system uses game environments to train and evaluate athletic skills for humanoid robots, providing a scalable and diverse testing platform for dynamic movements.

 Switch4EAI는 로봇 운동 능력 벤치마킹을 위해 콘솔 게임 플랫폼을 활용합니다. 시스템은 게임 환경을 사용하여 휴머노이드 로봇의 운동 기술을 훈련하고 평가하며, 동적 움직임을 위한 확장 가능하고 다양한 테스트 플랫폼을 제공합니다.

### Key Features
- Console game platform integration
- Athletic skill benchmarking
- Scalable training environment
- Diverse motion testing
- Game-based skill evaluation

---

## DeepMimic: Example-Guided Deep Reinforcement Learning of Physics-Based Character Skills

**Authors**: Xue Bin Peng, Pieter Abbeel, Sergey Levine, Michiel van de Panne

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/1804.02717)
- 🌐 [Project](https://xbpeng.github.io/projects/DeepMimic/index.html)
- 💻 [GitHub](https://github.com/xbpeng/DeepMimic)

### 요약 (Summary)

 DeepMimic presents a data-driven approach to physics-based character animation using deep reinforcement learning. The system learns to imitate reference motion clips through RL, enabling characters to perform a wide variety of challenging skills including locomotion, acrobatics, and martial arts.

 DeepMimic은 심층 강화학습을 사용한 물리 기반 캐릭터 애니메이션에 대한 데이터 기반 접근법을 제시합니다. 이 시스템은 RL을 통해 참조 모션 클립을 모방하는 방법을 학습하여 캐릭터가 보행, 곡예, 무술을 포함한 다양한 도전적인 기술을 수행할 수 있게 합니다.

### Key Features
- Physics-based character control
- Example-guided reinforcement learning
- Diverse skill learning (locomotion, acrobatics, martial arts)
- Motion imitation framework
- Deep RL for character animation

---
[Back to Main README](../README.md)
