<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-kkcjy.github.io-5B7A99?style=for-the-badge&logo=github&logoColor=white)](https://kkcjy.github.io)

<a href="https://github.com/kkcjy">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:5B7A99,100:4E8A8A&height=170&section=header&text=Junxian%20Jin&fontSize=44&fontColor=ffffff&desc=AI%20%2F%20Backend%20Engineer&descSize=17&descAlignY=56" alt="Junxian Jin" />
</a>

## ✦ 金俊贤 · Junxian Jin ✦

**东南大学 · 计算机科学与技术**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&pause=1000&color=5B7A99&width=460&lines=RAG+%C2%B7+LLM+%C2%B7+Embedded;Vibe+Coding+%C2%B7+Skills+%C2%B7+MCP;Wireless+Protocols+%C2%B7+TDoA+%2F+DSR)](https://github.com/kkcjy)

[![GitHub followers](https://img.shields.io/github/followers/kkcjy?style=social)](https://github.com/kkcjy)
[![Profile views](https://komarev.com/ghpvc/?username=kkcjy&color=5B7A99&style=flat-square)](https://github.com/kkcjy)

</div>

---

### 🌸 关于我 About Me

- 🔭 正在构建 [**RAG-LAB**](https://github.com/kkcjy/RAG-LAB) —— RAG 知识库问答系统
- 🧪 AI 工程实践：Vibe Coding · Skills · Memory · MCP Server · Harness 工程
- 📡 硬件与协议：Crazyflie 2.1 · DW3000 · FreeRTOS · TDoA / DSR

---

### 🛠️ 技能 Skills

**AI / LLM**

![RAG](https://img.shields.io/badge/RAG-5B7A99?style=for-the-badge)
![Vibe Coding](https://img.shields.io/badge/Vibe_Coding-4E8A8A?style=for-the-badge)
![MCP Server](https://img.shields.io/badge/MCP_Server-6A8A66?style=for-the-badge)
![Claude Skills](https://img.shields.io/badge/Claude_Skills-A88A58?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-7A6B96?style=for-the-badge&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-A07088?style=for-the-badge&logo=pytorch&logoColor=white)
![MindSpore](https://img.shields.io/badge/MindSpore-6E7A88?style=for-the-badge)

**嵌入式 / 协议**

![C](https://img.shields.io/badge/C-5B7A99?style=for-the-badge&logo=c&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4E8A8A?style=for-the-badge)
![TDoA](https://img.shields.io/badge/TDoA-6A8A66?style=for-the-badge)
![UWB](https://img.shields.io/badge/UWB-A88A58?style=for-the-badge)
![SolidWorks](https://img.shields.io/badge/SolidWorks-7A6B96?style=for-the-badge)

**工程 / 数据**

![Python](https://img.shields.io/badge/Python-5B7A99?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-4E8A8A?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-6A8A66?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-A07088?style=for-the-badge&logo=linux&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-A88A58?style=for-the-badge&logo=redis&logoColor=white)

---

### 💼 项目 Projects

#### ⭐ RAG-LAB — RAG 知识库问答系统

`FastAPI` `Qdrant` `PostgreSQL` `Redis` `DeepSeek` `BGE-M3` `vLLM` `Docker`

通用文档入库 → 本地向量检索 → 联网兜底的全流程 RAG，多用户 + 细粒度权限 + 全量审计。

- Query 改写 · 相关度判定（阈值 + LLM 精判）· SSE 流式输出带引用标注
- 扫描件 PDF 自动 OCR（本地 RapidOCR）· 中文友好分块 · 增量索引
- Provider 抽象层：LLM / Embedding / 向量库 / 联网搜索 —— 改配置即切换

📁 相关仓库：[RAG-LAB](https://github.com/kkcjy/RAG-LAB)

#### 🌐 文枢多模态智能翻译系统

`FastAPI` `DeepSeek-R1` `Qwen3` `MindSpore` `Transformer`

本地化部署开源大模型，自研高精度 / 高速两套 Transformer 翻译模型，支持复杂文档与图片的中英文实时互译。

- 高精度模型 BLEU：中译英 **20.30** / 英译中 **25.37** · WMT-21 数据集训练
- 高速模型端到端响应 **< 500 ms**

📁 相关仓库：[Translator](https://github.com/kkcjy/Translator)

#### 📡 DSR 路由算法与多 Agent 集群测距系统

`C` `TDoA` `DSR` `Crazyflie 2.1` `DW3000` `FreeRTOS`

针对传统 DS-TWR 在动态智能体集群中的测距滞后问题，提出 **DSR 算法**，设计兼容 TDoA 报文格式的专用协议栈与状态机，支持测距模式无缝切换。

- 测距精度提升：Mean AE ↓ **37.6%** · RMSE ↓ **32.1%** · MRE ↓ **36.7%**
- **第一发明人**发明专利授权（[ZL 2025 1 1363809.5](patent-ZL2025113638095.pdf)）· 论文 **MobiCom 在投**

📁 相关仓库：[TDoA-DSR-Compat-Framework](https://github.com/kkcjy/TDoA-DSR-Compat-Framework) · [drone-communication-simulation-system](https://github.com/kkcjy/drone-communication-simulation-system)

---

### 📊 GitHub 统计

<div align="center">

<img src="https://streak-stats.demolab.com/?user=kkcjy&hide_border=true&background=F6F8FA&ring=5B7A99&fire=CB9A5E&currStreakNum=5B7A99&sideNums=5B7A99&currStreakLabel=5B7A99&sideLabels=5B7A99&dates=5B7A99" alt="GitHub streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kkcjy&layout=compact&title_color=5B7A99&text_color=57606A&bg_color=F6F8FA&hide_border=true" alt="Top languages" />

</div>

---

### 📮 联系 Contact

- 📧 Email：[kkcjy63@gmail.com](mailto:kkcjy63@gmail.com)

---

<div align="center">
  <sub>Built with 💜 by Junxian Jin</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5B7A99,100:4E8A8A&height=120&section=footer" alt="footer" />
