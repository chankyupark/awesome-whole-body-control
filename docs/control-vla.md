# Whole-Body Control + VLA (Vision-Language-Action)

비전-언어-행동 모델 기반 제어 - Vision-Language-Action models for humanoid control

---

## DreamControl: Human-Inspired Whole-Body Humanoid Control for Scene Interaction via Guided Diffusion

**Authors**: Dvij Kalaria, Sudarshan Harithas, Pushkal Katara, Sangkyung Kwak, Sarthak Bhagat, S. Shankar Sastry, Srinath Sridhar, Sai Vemprala, Ashish Kapoor, Jonathan Huang

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2509.14353)
- 🌐 [Project Page](https://genrobo.github.io/DreamControl/)
- 💻 GitHub: TBA (Coming Soon)

### 요약 (Summary)

 DreamControl introduces a novel methodology for learning autonomous whole-body humanoid skills. DreamControl leverages the strengths of diffusion models and Reinforcement Learning (RL): the core innovation is the use of a diffusion prior trained on human motion data, which subsequently guides an RL policy in simulation to complete specific tasks of interest (e.g., opening a drawer or picking up an object). The system demonstrates that this human motion-informed prior allows RL to discover solutions unattainable by direct RL, and that diffusion models inherently promote natural-looking motions, aiding in sim-to-real transfer. DreamControl validates its effectiveness on a Unitree G1 robot across diverse challenging tasks involving simultaneous lower and upper body control and object interaction, including opening drawers, bimanual picking, pressing buttons, and more.

 DreamControl은 자율 전신 휴머노이드 기술 학습을 위한 새로운 방법론을 소개합니다. DreamControl은 확산 모델과 강화학습(RL)의 강점을 활용합니다: 핵심 혁신은 인간 동작 데이터로 훈련된 확산 사전을 사용하는 것이며, 이는 시뮬레이션에서 RL 정책을 안내하여 특정 관심 작업(예: 서랍 열기 또는 물체 집기)을 완료하도록 합니다. 시스템은 이 인간 동작 정보가 담긴 사전이 RL이 직접 RL로는 달성할 수 없는 솔루션을 발견할 수 있게 하고, 확산 모델이 본질적으로 자연스러운 동작을 촉진하여 실제-실제 전이를 돕는다는 것을 보여줍니다. DreamControl은 서랍 열기, 양손 집기, 버튼 누르기 등을 포함하여 동시 하체 및 상체 제어와 물체 상호작용을 포함하는 다양한 도전적인 작업에서 Unitree G1 로봇에 대한 효과를 검증합니다.

### Key Features
- Diffusion-guided RL for humanoid control
- Human motion-informed priors
- Whole-body scene interaction
- Multiple task capabilities (drawer, picking, button pressing)
- Natural motion generation
- Sim-to-real transfer
- OmniControl diffusion model integration

---

## LeVERB: Humanoid Whole-Body Control with Latent Vision-Language Instruction

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2506.13751)
- 🌐 [Project](https://ember-lab-berkeley.github.io/LeVERB-Website/)
- 💻 GitHub: TBA (Coming Soon)
### 요약 (Summary)

 LeVERB introduces humanoid whole-body control with latent vision-language instruction. The system uses latent representations learned from vision and language to guide humanoid control, enabling more robust and generalizable behavior across diverse tasks and environments.

 LeVERB는 잠재 비전-언어 지시를 사용한 휴머노이드 전신 제어를 소개합니다. 시스템은 비전과 언어로부터 학습한 잠재 표현을 사용하여 휴머노이드 제어를 안내하며, 다양한 작업과 환경에서 더 견고하고 일반화 가능한 행동을 가능하게 합니다.

### Key Features
- Latent vision-language representations
- Multimodal instruction following
- Whole-body control integration
- Robust task generalization
- Vision-language alignment

---

## LangWBC: Language-directed Humanoid Whole-Body Control via End-to-end Learning

**Authors**: Yiyang Shao, Bike Zhang, Qiayuan Liao, Xiaoyu Huang, Yuman Gao, Yufeng Chi, Zhongyu Li, Sophia Shao, Koushil Sreenath

**Links**:
- 📄 [arXiv](https://arxiv.org/abs/2504.21738)
- 🌐 [Project](https://langwbc.github.io/)
- 💻 [GitHub](https://github.com/YiyangShao2003/LangWBC)

### 요약 (Summary)

 LangWBC presents a language-directed humanoid whole-body control system via end-to-end learning. The system enables users to control humanoids using natural language commands, translating high-level linguistic instructions into coordinated whole-body motions. This bridges the gap between human intent expressed through language and robot execution.

 LangWBC는 엔드투엔드 학습을 통한 언어 지향 휴머노이드 전신 제어 시스템을 제시합니다. 시스템은 사용자가 자연어 명령을 사용하여 휴머노이드를 제어할 수 있게 하며, 고수준 언어 지시를 협응된 전신 동작으로 변환합니다. 이는 언어를 통해 표현된 인간의 의도와 로봇 실행 사이의 격차를 연결합니다.

### Key Features
- Natural language control interface
- End-to-end learning framework
- High-level command interpretation
- Whole-body motion generation from language
- Language-to-action translation

---




[Back to Main README](../README.md)
