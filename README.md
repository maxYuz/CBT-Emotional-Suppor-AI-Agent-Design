# CBT-AI-Emotional-Suppor-Agent
# 基于CBT 情绪感支持 AI Agent

An AI emotional support agent designed based on Cognitive Behavioral Therapy (CBT) principles.  
It emphasizes multi-turn dialogue, relationship building, and interaction flows inspired by real psychological consultation structures.  
（基于认知行为疗法 CBT 设计的 AI 情绪支持智能体；强调多轮对话、关系建立、体验类真实心理咨询结构与互动流程）

---

# 1. Project Overview
# 1. 项目简介

This project designs an AI agent for psychological growth and emotional support using CBT principles.  
It leverages prompt engineering and multi-node workflow architecture to guide interactions in a structured, template-based way.  
-本项目是一个基于认知行为疗法（Cognitive Behavioral Therapy, CBT）-心理咨询理论方法设计的 AI 心理成长、情绪支持智能体。通过将心理辅导应用于语言大模型，以流程模版化、结构化与类真实心理互助的对话，帮助用户进行日常的情绪觉察与认知反思。
该智能体通过Prompt Engineering + 多节点Workflow 工作流架构进行构建，使AI在对话过程中能够按照一定的心理支持逻辑进行互动，而不是简单的随机聊天。

The AI agent guides users through four progressive stages based on relational intimacy:
在对话过程中，智能体根据亲密度判定会逐步引导用户进入到四个阶段：

1. Pre-Engagement / 咨询建立前期  
   Build and maintain dialogue rapport, provide empathy, and establish conversation direction.  
   （建立与保持稳定的对话关系，提供共情与咨询方向确立）

2. Early Engagement / 咨询中前期  
   Help users describe specific psychological concerns, identify triggers behind emotions, and structure dialogue.  
   （引导用户描述心理问题，识别情绪触发情境，推进结构化流程）

3.  Late Engagement / 咨询中后期  
   Apply CBT principles to help users reframe negative cognitions and support psychological growth.  
   （利用 CBT 改变负面认知，让用户体验心理成长）

4. Closure / 咨询后期 
   Encourage continued cognitive or behavioral experimentation.  
   （鼓励用户尝试新的认知或行为视角）

> ⚠️ This AI agent is for emotional support and self-awareness only. It is **not** a substitute for medical diagnosis or professional psychological treatment.  
> （仅用于情绪支持与自我觉察辅助，不提供医疗诊断或专业心理治疗）

---

# 2. Project Goals
#2. 项目目标

- Explore whether AI can provide structured, process-oriented, and human-like emotional support experiences.  
  （探索 AI 是否可提供结构化、流程化、类心理互助的情绪支持体验）  

- Apply CBT and humanistic psychology principles to AI dialogue logic design.  
  （通过 CBT 与人本主义心理学方法设计 AI 对话逻辑）  

- Use workflow architecture to enhance emotional interaction, stability, and controllability of AI Agent.  
  （通过 Workflow 架构提升 AI Agent 情感互动、稳定性与可控性）  

- Establish safety and ethical mechanisms in emotional support scenarios.  
  （在心理支持场景中建立安全与伦理机制）

---

# 3. Agent Design Approach
# 3. Agent设计思路

3.1 Structured Psychological Dialogue / 心理学结构化对话

- Traditional AI companions often only offer empathy without structure.  
- This project integrates CBT and humanistic psychology principles for stepwise guidance.  
- CBT provides clear structure and modular techniques suitable for dialogue workflows.  
- Humanistic approach emphasizes relationship building and supportive conversation atmosphere.  
（如何让 AI 对话具有心理学结构（咨询流程化、模版化、情感互动性强）
许多 AI 情绪陪伴产品的问题是：只停留在安慰与共情；缺乏结构化、理论化、连续性的心理支持、情感互动与问题解决。
因此本项目选择 CBT（认知行为疗法）与人本主义心理学流派（整合取向） 作为对话设计基础，因为 CBT 具有：结构清晰-具有明确的咨询流程与干预逻辑、心理咨询技术模块化-技术可以拆分为对话步骤、标准化搞-易转化为对话流设计；而人本主义具有：重视关系建立与维持、支持性对话氛围。
通过拆解 CBT与人本主义心理学技术，使AI可以逐步引导用户进行心理辅助。）

 3.2 Dialogue Stage Control / 对话阶段控制

- Early cognitive analysis may feel directive to users.  
- Multi-turn staged dialogues manage relational progression:  
  Pre-Engagement → Early Engagement → Late Engagement → Closure  
- Relational intimacy and memory retrieval help adjust dialogue stage dynamically.  

（在真实心理咨询中，如果咨询师过早进行认知分析，用户容易产生被分析或被指导的感受，不利于用户黏性与使用体验。
因此本项目采用 多轮阶段化对话设计：
基于关系判断进行：咨访关系建立 → 咨访关系中前期 → 咨访关系中后期 → 咨访关系后期
通过阶段控制技术、灵活调整亲密度、长期以及读取分析，让对话更加自然。）

3.3 Stability & Emotional Consistency / 对话稳定性与情感一致性

- Long conversations risk style drift, logic disruption, or inconsistent emotional expression.  
- Controlled via:  
  1. *Prompt Engineering*: constrain AI behavior, empathy, tone, response strategy, stage rules, psychological technique timing.  
  2. *Workflow Management*: multi-node workflow with memory retrieval ensures smooth stage transition and emotional support continuity.  

（大模型在长对话中容易出现：回复风格漂移；技术使用混乱；对话逻辑不稳定；情感回不一致或缺乏持续性。
然而，在情绪支持与心理对话场景中，用户不仅需要逻辑清晰的回应，还需要稳定、连续的情感互动体验。如果 AI 在不同回复中表现出明显的情绪风格变化，容易破坏用户的信任感与对话沉浸感。
因此，本项目在设计中同时关注对话结构稳定性与情感互动体验，并通过以下方式进行控制：
a.Prompt Engineering
-通过系统 Prompt 对 AI 的回应风格进行约束，包括：
角色（身份规则）、共情表达方式、语气与互动风格、回答策略、关系亲密度规则、阶段规则、心理技术的使用时机、规避风险。
从而保证 AI 在整个对话过程中保持稳定的情感表达与支持性互动风格。
b.Workflow 对话控制
-通过阶段化、多节点 Workflow 管理对话流程，以长期记忆为基础，根据大模型判断亲密度，进入不同咨询阶段使用不同的对话策略，使 AI 在与用户不同阶段罐子中情感支持、问题探索与认知引导之间形成自然过渡。
通过这种设计，系统能够在结构化心理支持与自然情感互动之间保持平衡，从而构建一个既具有心理学逻辑，又具备稳定情感体验的AI对话系统。）

---

# 4 Agent Architecture
# 智能体架构设计

This document describes the architecture of the Emotion-Aware AI Agent.  
（本文档说明情绪感知 AI Agent 的架构设计）

---

#Core Modules
# 核心模块

1. User Input / 用户输入 
   - Receive and preprocess user messages  
   - 接收并预处理用户输入

2. Emotion Detection & State Analysis / 情绪感知与状态分析  
   - Detect emotional cues, tone, and context  
   - 分析情绪、语气和上下文

**→ Memory Storage & Retrieval / 记忆库存取**  
   - Maintain long-term memory of previous conversations  
   - Use retrieval prompts to fetch relevant information for context  
   - 长期记忆库保存历史对话，并通过规则 prompt 检索上下文相关信息

3. Stage Classification / 对话阶段分类  
   - Determine the conversation stage: Engagement / Exploration / Intervention / Closure  
   - 判断对话阶段：建立 / 探索 / 干预 / 结束

4. Prompt Selection & Response Strategy / Prompt 选择与响应策略
   - Select appropriate prompts based on stage  
   - Generate AI response plan  
   - 根据阶段选择 Prompt 并生成响应策略

**→ Sentence Segmentation & Pause Handling / 断句与停顿处理**  
   - Improve realism of AI output with controlled pauses  
   - 可通过断句和停顿处理，让 AI 回复更自然、像真人

5. Response Generation / 响应生成  
   - Generate the final AI message to the user  
   - 输出最终响应，并更新阶段状态

---

> Modular design allows updating prompts, memory rules, or pause handling independently.  
> （模块化设计，可独立更新 Prompt、记忆规则或停顿处理逻辑）

Emotion-Aware-AI-Agent/
├── README.md
├── prompt_architecture/
│   ├── stage1_engagement.md
│   ├── stage2_exploration.md
│   ├── stage3_intervention.md
│   ├── stage4_closure.md
│   └── memory_retrieval_rules.md  
├── agent_workflow/
│   └── workflow_diagram.md
├── system_design/
│   └── agent_architecture.md     
├── conversation_examples/
└── output_processing/
    └── sentence_pause_handling.md
    

---


# 6. Use Cases
# 6. 项目使用场景

- Daily emotional reflection  
- Stress and concern analysis  
- Automated cognitive awareness  
- Emotion expression and journaling  

Example input:  
> "I feel like I can't do anything right recently"  
> "Work has been overwhelming lately"  
> "I keep thinking about past mistakes"  

The agent guides users through multi-turn, structured, stage-based dialogue for emotional support and cognitive reflection.  
（用户通过多轮阶段化对话，进行情绪梳理、认知反思和心理辅助）

---

# 7. Limitations
# 7. 项目局限

- Not a replacement for professional psychological counseling  
- Does not provide medical diagnosis, mental illness treatment, or crisis intervention  
- Users in severe psychological distress should seek professional help  
（不能替代专业心理咨询；不提供医疗诊断、精神疾病治疗或危机干预；严重心理困扰应寻求专业支持）
