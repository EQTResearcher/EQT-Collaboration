name: 🌱 新EQT研究提案
description: 提交新的EQT研究思路
body:
  - type: textarea
    id: idea
    attributes:
      label: "研究思路"
      description: "描述你的核心假设和研究问题"
      placeholder: "例：基于EQT框架，预测XXX现象的数学结构为..."
    validations:
      required: true
  
  - type: textarea
    id: prediction
    attributes:
      label: "可检验预测"
      description: "具体可验证的结果或模式"
      placeholder: "例：数值模拟应显示周期性振荡，频率为..."
  
  - type: dropdown
    id: priority
    attributes:
      label: "优先级"
      options:
        - "🔥 高优先级"
        - "⚡ 快速验证"
        - "🔍 中等优先级"
  
  - type: dropdown
    id: domain
    attributes:
      label: "研究领域"
      options:
        - "🧮 数学基础"
        - "🔬 实验验证"
        - "🧠 AI/ML方法"
        - "🌌 宇宙学应用"
  
  - type: textarea
    id: ai_needs
    attributes:
      label: "AI辅助需求"
      description: "列出需要AI Bot帮助的部分"
      placeholder: "@EQT-AI-Bot 验证数学推导 @EQT-AI-Bot 生成数值模拟"
