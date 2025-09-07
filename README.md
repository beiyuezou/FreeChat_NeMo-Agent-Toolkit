FreeChat--AI多智能体交流应用

<img width="918" height="522" alt="截屏2025-09-07 下午9 30 16" src="https://github.com/user-attachments/assets/e78a1b17-8563-4bc4-b6dc-04fa3c840430" />



🎯 项目简介
FreeChat为聋哑人与热心人士打造的双向交流应用。项目为NVIDIA NeMo Agent Toolkit的基础上二次开发。以画布、图标、emoji、文生图等方式，促进双向交流。

✨ 核心特性
🤖官方架构：NVIDIA官方NeMo Agent Toolkit
画布：可以用画画的方式来表达意图
图标：常用的生活场景细分图标，用图标来交流
emoji：用来表达基本的情感
文生图：用文字描述，AI转化成图像形式呈现交流意图
LLM：采用英伟达的框架、使用阿里百炼平台提供的API
多agent：协调管理、意图理解、情感分析、视觉生成、翻译转换、紧急响应、智能响应。
mcp：支持上下文协议

                                                           画布

<img width="462" height="539" alt="image" src="https://github.com/user-attachments/assets/b6aba189-0f9b-46cc-aeb3-c93abd646da4" />




                                                       无障碍计算器

<img width="462" height="820" alt="image" src="https://github.com/user-attachments/assets/f2eb7ac8-5e4e-4df6-ac0d-58c79f0d95d7" />




                                                        emoji

<img width="462" height="820" alt="image" src="https://github.com/user-attachments/assets/5f0e9ef7-5bc4-4bc0-ab91-0281a2f65c59" />



 

                                                         图标

<img width="462" height="820" alt="image" src="https://github.com/user-attachments/assets/38decfc1-48de-49f4-a404-22115a90e369" />






                                                        文生图

<img width="462" height="509" alt="image" src="https://github.com/user-attachments/assets/50004e51-5c18-4829-b903-a80eb95a7af4" />







Agent工作流程
用户输入
   ↓
[协调管理Agent] → 分配任务
   ↓
[意图理解Agent] → 理解用户需求
   ↓
[情感分析Agent] → 识别情绪状态
   ↓
[视觉生成Agent] → 转换为图标/表情
   ↓
[翻译转换Agent] → 多模态转换
   ↓
[紧急响应Agent] → 处理紧急情况
   ↓
智能响应输出


🏗️技术架构
前端
框架：Next.js 14 + TypeScript
UI库：官方NeMo-Agent-Toolkit-UI
特点：可在离线下使用、智能响应尚在开发中
的
核心：NVIDIA NeMo Agent 工具包（AIQ）
工作流程：React Agent
工具：Tavilly搜索、时间查询
模型支持
默认：Qwen模型等阿里百炼平台API
兼容：任何OpenAI格式的API
自定义：用户可API密钥、模型名称、配置base_url


Demo link:https://beiyuezou.github.io/FreeChat_NeMo-Agent-Toolkit/freechat-app.html

Demo video:https://www.youtube.com/shorts/S4VJJ6X3fW4

