# Whole-Body Control + Locomotion

전신 제어와 이동의 통합 - Integration of manipulation and walking

---

## Expert-Guided Imitation for Learning Humanoid Loco-Manipulation from Motion Capture

**Authors**: Rohan P. Singh, Pierre-Alexandre Leziart, Masaki Murooka, Mitsuharu Morisawa, Eiichi Yoshida, Fumio Kanehiro

**Links**:
- 📄 arXiv: TBA
- 🌐 Project Page: TBA

### 요약 (Summary)

**English**: This work presents an expert-guided imitation learning framework for humanoid loco-manipulation from motion capture data. The system combines locomotion and manipulation skills learned from human demonstrations, enabling humanoids to perform coordinated whole-body tasks while moving.

**한글**: 이 연구는 모션 캡처 데이터로부터 휴머노이드 로코-매니퓰레이션을 위한 전문가 가이드 모방 학습 프레임워크를 제시합니다. 시스템은 인간 시연으로부터 학습한 이동과 조작 기술을 결합하여 휴머노이드가 이동하면서 협응된 전신 작업을 수행할 수 있게 합니다.

### Key Features
- Expert-guided imitation learning
- Motion capture-based training
- Coordinated loco-manipulation
- Whole-body skill integration
- Real-world humanoid deployment

---

## GMT: General Motion Tracking for Humanoid Whole-Body Control

**Authors**: Zixuan Chen, Mazeyu Ji, Xuxin Cheng, Xuanbin Peng, Xue Bin Peng, Xiaolong Wang

**Year**: 2025

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2506.14770)
- 🌐 [Project Page](https://gmt-humanoid.github.io/)
- 💻 [GitHub](https://github.com/zixuan417/humanoid-general-motion-tracking)

### 요약 (Summary)

**English**: GMT proposes a general and scalable motion-tracking framework that trains a single unified policy to enable humanoid robots to track diverse motions in the real world. GMT is built upon two core components: an Adaptive Sampling strategy and a Motion Mixture-of-Experts (MoE) architecture. The Adaptive Sampling automatically balances easy and difficult motions during training, while the MoE ensures better specialization of different regions of the motion manifold. GMT achieves state-of-the-art performance across a broad spectrum of motions using a unified general policy, including stretching, kicking, dancing, high kicking, kung-fu, boxing, running, side stepping, and squatting.

**한글**: GMT는 휴머노이드 로봇이 실제 세계에서 다양한 동작을 추적할 수 있도록 단일 통합 정책을 훈련하는 일반적이고 확장 가능한 모션 추적 프레임워크를 제안합니다. GMT는 두 가지 핵심 구성 요소인 적응형 샘플링 전략과 모션 Mixture-of-Experts (MoE) 아키텍처를 기반으로 합니다. 적응형 샘플링은 훈련 중 쉬운 동작과 어려운 동작의 균형을 자동으로 맞추고, MoE는 모션 매니폴드의 다른 영역에 대한 더 나은 전문화를 보장합니다. GMT는 스트레칭, 킥, 댄스, 하이 킥, 쿵푸, 복싱, 달리기, 측면 스텝, 스쿼트를 포함한 광범위한 동작 스펙트럼에 걸쳐 통합 일반 정책을 사용하여 최첨단 성능을 달성합니다.

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
- 💻 GitHub: TBA

### 요약 (Summary)

**English**: BeyondMimic presents a real-world framework to learn from human motions for versatile and naturalistic humanoid control via guided diffusion. The framework provides a motion tracking pipeline capable of challenging skills such as jumping spins, sprinting, and cartwheels with state-of-the-art motion quality. Moving beyond simply mimicking existing motions, BeyondMimic introduces a unified diffusion policy that enables zero-shot task-specific control at test time using simple cost functions. Deployed on hardware, BeyondMimic performs diverse tasks at test time, including waypoint navigation, joystick teleoperation, and obstacle avoidance, bridging sim-to-real motion tracking and flexible synthesis of human motion primitives for whole-body control.

**한글**: BeyondMimic은 가이드 확산을 통한 다재다능하고 자연스러운 휴머노이드 제어를 위해 인간 동작으로부터 학습하는 실제 세계 프레임워크를 제시합니다. 프레임워크는 최첨단 모션 품질로 점프 스핀, 전력 질주, 재주넘기와 같은 도전적인 기술이 가능한 모션 추적 파이프라인을 제공합니다. 기존 동작을 단순히 모방하는 것을 넘어, BeyondMimic은 간단한 비용 함수를 사용하여 테스트 시점에 제로샷 작업별 제어를 가능하게 하는 통합 확산 정책을 도입합니다. 하드웨어에 배치된 BeyondMimic은 경유지 네비게이션, 조이스틱 원격조작, 장애물 회피를 포함한 다양한 작업을 테스트 시점에 수행하여 전신 제어를 위한 실제-실제 모션 추적과 인간 모션 프리미티브의 유연한 합성을 연결합니다.

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

[Back to Main README](../README.md)
