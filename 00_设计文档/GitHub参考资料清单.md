# GitHub 企业/制造业 AI 培训参考资料清单

> 调研时间：2026-08-23
> 用途：为"面向制造业、技术小白起点、初级/中级/高级三档"企业 AI 培训产品，寻找"完整体系+全套资料"的 GitHub 底本，先复制再改造。

## 一、结论
GitHub 上存在多个"完整课程体系 + 全套课件资料"的仓库，可直接 fork/克隆后改造。最匹配"制造业+AI+全套资料包"的是 **tertiarycourses/AI-For-Lean-Manufacturing**（连 PPT/学员手册/教案/带数据的活动包都齐）。

## 二、按分级推荐

### 初级 · 通识基础（技术小白起点）
1. **microsoft/generative-ai-for-beginners**（~11万★，MIT）
   - 21课：提示词→文本/图像/搜索应用→RAG→Agent→微调→SLM
   - 每课含短视频+README+Python/TS代码+拓展资源
   - 含官方"企业培训计划"场景（全员普及→技术培训→高级应用）
   - URL: https://github.com/microsoft/Generative-AI-for-beginners
2. **microsoft/AI-For-Beginners**（~4万★，MIT）
   - 12周24课：AI史/符号AI/神经网络/CV/NLP/遗传算法/多智能体/AI伦理
   - 含课前课后测验+可执行 Notebook 实验+多语言
   - URL: https://github.com/microsoft/AI-For-Beginners

### 中级 · 制造业场景落地
3. **tertiarycourses/TGS-2023020425-AI-For-Lean-Manufacturing**（© Tertiary Infotech，学员向课件公开）
   - 2天课程，精益制造 × 制造业 AI
   - **完整资料包**：可编辑 PPT 讲师 deck+PDF、学员手册(Word/MD/PDF)、教案(Word/PDF)、10个活动文件夹(场景+模拟数据+工作表+证据清单)、可编辑 PPT 图表
   - 10活动：浪费扫描/AI机会、SIPOC价值流、产能节拍瓶颈、ABC库存、EBQ-Kanban、5Why鱼骨、AI视觉质检、预测维护决策、接地GenAI标准作业、Lean-AI试点章程(ROI/PDCA)
   - 注意：考核卷/答案/参考书目为私有未公开
   - URL: https://github.com/tertiarycourses/TGS-2023020425-AI-For-Lean-Manufacturing
4. **adhityarenato99/Industrial-AI-Transforming-Modern-Manufacturing**（公开）
   - 24h/8节：预测维护/视觉质检/生产优化供应链/GenAI-RAG/实施治理/迷你项目
   - 含完整 syllabus、迷你项目选项、考核权重（Quiz15%实践35%案例20%项目30%）
   - URL: https://github.com/adhityarenato99/Industrial-AI-Transforming-Modern-Manufacturing

### 高级 · 技术深度与规划
5. **KAIST iailab/ai-for-smart-manufacturing**（开放可改）
   - 智能制造成体系课件：视觉AI质检/时序分析/信号学习/预测维护/可解释AI/物理信息AI/Agentic AI与LLM
   - 含 HTML/Colab/Slides/PowerPoints/习题/答案
   - URL: https://iailab.kaist.ac.kr/teaching/ai-for-smart-manufacturing
6. **ai-infra-curriculum**（22库11轨，公开）
   - 极完整的 AI 基础设施/MLOps/平台工程课程体系，数百练习+真实项目
   - 偏工程深度，技术小白偏深，可作高级技术参考
   - URL: https://github.com/ai-infra-curriculum

### 参考索引
7. **joshuamschultz/enterprise-ai-resources**（公开）
   - 企业级 AI 资源/学习路径/工具链索引（RAG流程、Agent、MLOps、云平台）
   - URL: https://github.com/joshuamschultz/enterprise-ai-resources

## 三、与我们总大纲的映射
- 初级 → microsoft 两套（MIT，可随意改造）
- 中级 → tertiarycourses（完整资料包母体）+ Industrial-AI（制造业实战）
- 高级 → KAIST（技术深度）+ GitHub 企业赋能八支柱（组织落地，见总大纲）
- 参考索引 → enterprise-ai-resources / ai-infra-curriculum

## 四、下一步（待用户确认）
- 方案A：直接克隆上述仓库到本地 workspace，开始"复制改造"
- 方案B：先以 tertiarycourses 中级资料包为样本，产出我们第一套 PPT 样章
- 方案C：仅作素材引用，不克隆，保持我们原创结构
