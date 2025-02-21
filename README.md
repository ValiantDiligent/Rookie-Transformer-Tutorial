# Rookie-Transformer-Tutorial
本项目通过纯手写实现Transformer核心组件及训练推理代码，尽可能少调用现成深度学习框架的高级封装接口，旨在为学习者提供"白盒级"的Transformer实现参考。代码包含注释，适合希望深入理解Transformer机制的新手开发者。

## 项目简介 📖  
本项目通过纯手写实现Transformer核心组件和训练推理代码，尽可能少的直接调用现成深度学习框架的高级封装接口，旨在为学习者提供"白盒级"的Transformer实现参考。代码包含注释、特别适合希望深入理解LLM底层机制的新手开发者。如果对您有帮助，可以点Star，跟踪最新的更新。

## 核心实现 🔥  

### 注意力机制全家桶
- ✅ Multi-Head Attention (MHA)
- ✅ Multi-Query Attention (MQA)
- ✅ Grouped-Query Attention

### 归一化层对比实现
对CV场景和NLP场景的Norm方式都做了实现，后续会更新相关技术博客。

- ✅ BatchNorm (BN)  
- ✅ LayerNorm (LN) 
- ✅ RMSNorm 

### 推理优化技术
- ✅ KV Cache机制实现（减少重复计算）  
- ✅ 自回归解码的token-by-token生成  



## 项目亮点 ✨  
- 🚀 包含极简训练示例（CPU可跑的小规模语言模型）  
- 📚 配套相关文档链接  


## 适合人群 🎯  
- 希望摆脱"调包侠"身份的LLM学习者  
- 面试前需要手撕Transformer的求职者  


## 后续计划 🚧  
- [ ] 增加Flash Attention模拟实现
- [ ] 增加MLA的支持
- [ ] 添加量化和LoRA相关示例  
- [ ] 提供交互式训练可视化面板  

---
