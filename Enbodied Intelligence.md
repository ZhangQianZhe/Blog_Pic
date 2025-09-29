## 论文基本信息
- **标题**：Embodied Intelligence: A Synergy of Morphology, Action, Perception and Learning  
- **作者**：
  HUAPING LIU, Tsinghua University, Beijing, China 
  DI GUO, Beijing University of Posts and Telecommunications, Beijing, China 
  ANGELO CANGELOSI, The University of Manchester, Manchester, United Kingdom of Great Britain and Northern Ireland  
- **来源/会议/期刊**：  ACM Comput. Surv. 57, 7, Article 186 (March 2025), 36 pages.
- **年份**：2025  
- **DOI/链接**：https://doi.org/10.1145/3717059
  
---
## 📝 摘要 (Abstract)
- The tight coupling of brain,body and enviorment(苏似乎提到过解耦的方法，包括子Model和skill chain)
- 形态(synergy)、行动(morphology)、action and Learning 之间的联系，和基于此的未来研究方向
  
## 📚 Introduction
- Embodied intelligence is the computational approach to the design and understanding of intelligent behavior in embodied and situated agents through the consideration of the strict coupling between the agent and its environment, mediated by the constraints of the agent’s own body, perceptual and motor system, and brain.（说的挺清楚的：智能体与环境间的耦合或者说相互作用，智能体自身身体、感知、动力的约束）
- It is continuously and dynamically generated through the process of information perception and physical interaction with the environment.(智能体的感知、智能体与环境的物理交互)
- the definition of an agent is perceiving its environment through sensors and acting upon that environment through actuators.(感知、执行)
- visual perception, language processing, and speech processing（视觉应该指图像和视频、语言应该是文本、语音应该是语音）
- However, the robotics field, which focuses more on action execution, has not achieved the same successful results yet. Furthermore, even in the aforementioned areas where great success has been achieved, it is mostly under the assumption of a restricted environment. Once it is for the open environment, current artificial intelligence techniques are still faced with huge challenges.(robotic field在行动执行上有所不足、另外在开放世界或者real world上不足)
- The core reason for this problem is that we have paid more attention to the perception and learning capabilities of the agent but have not fully explored the action and behavior capabilities of the agent.（智能体在行为和行动上的表现不足）
- disembodied intelligence（重点放在模拟大脑去做决策和理解行为，身体往往是被动的执行机构）
- 两类Paper:
  - physical intelligence等😂😂😂(没看懂、论文也下载不了)
  - 机器学习、计算机视觉、基础模型在一些具体topic上的研究,如VLN(视觉语言导航)、simulators.
  - 《From machine learning to robotics: Challenges and opportunities for embodied intelligence》系统讨论了具身智能的偏差；分析了形态、representation、learning的作用；描述了智能体与环境的能量交换.👍👍👍这篇文章只是强调机遇与挑战，可能方法上没有详细的描述
## ⏳ A Long Past and a Short History
- 感知与认知很难区分；感知-行为的闭环是认知的核心
- AI的发展很快也很有作用，但在智能体与Real World的交互上、可解释性上有很大的不足
- it is relatively easy for a computer to play chess like an adult, but it is quite difficult or even impossible for a computer to perceive and act like a 1-year-old child😂(有意思)
- disembodied intelligence has achieved great success in fields represented by Internet information processing, whereas embodied intelligence, which is highly relevant to mechanisms and materials, has become the core foundation of intelligent robots.👍(总结到位)
## 🧩 方法结构
