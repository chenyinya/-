# 🔬 陈一阳 | AI研究员  数学建模

<div align="center">

<a href="#"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&pause=1000&color=3584E4&center=true&vCenter=true&width=600&height=60&lines=图分+%7C+医学影像+%7C+时序预测+%7C+具身智能" alt="研究方向" /></a>
  
[![Python](https://img.shields.io/badge/Python-精通-3776AB?style=for-the-badge&logo=python)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-熟练-EE4C2C?style=for-the-badge&logo=pytorch)](https://pytorch.org/)
[![MATLAB](https://img.shields.io/badge/MATLAB-熟悉-0076A8?style=for-the-badge&logo=mathworks)](https://www.mathworks.com/)
[![SPSS](https://img.shields.io/badge/SPSSpro-熟练-052FAD?style=for-the-badge&logo=ibm)](https://www.ibm.com/spss)

[![Computer Vision](https://img.shields.io/badge/计算机视觉-经验丰富-brightgreen?style=for-the-badge&logo=opencv)](https://opencv.org/)
[![NLP](https://img.shields.io/badge/自然语言处理-技能熟练-blue?style=for-the-badge&logo=huggingface)](https://huggingface.co/)
[![Reinforcement Learning](https://img.shields.io/badge/强化学习-持续进阶-yellow?style=for-the-badge&logo=tensorflow)](https://gymnasium.farama.org/)
[![YOLO](https://img.shields.io/badge/YOLO-应用-00FFFF?style=for-the-badge&logo=darknet)](https://pjreddie.com/darknet/yolo/)

<img src="https://github-readme-stats.vercel.app/api?username=chenyinya&show_icons=true&theme=radical" alt="GitHub统计" />

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chenyinya&theme=radical" alt="GitHub连续贡献" />
</div>

## 🧠 研究方向

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=chenyinya&theme=dracula&column=4&margin-w=15&margin-h=15" alt="GitHub奖杯" />
</div>

我的研究涵盖了人工智能的多个前沿领域：

- 🖼️ **图分(图像分类与分割)** - 多尺度特征提取与融合架构，特征表征与哈希编码
- 🏥 **医学影像报告生成** - 记忆增强模型，基于动态记忆库的特征学习，临床专家眼动数据引导
- 📈 **时序预测** - 极端天气下的水文数据分析，极地坐标表征与多端序列建模
- 🤖 **具身智能** - 基于强化学习的机器人控制模型，分层时序差分学习，端到端训练框架

## 🛠️ 技术栈

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>编程语言与框架</h3>
      <ul>
        <li>Python (高级)</li>
        <li>PyTorch / LORA</li>
        <li>MATLAB</li>
        <li>SPSSpro / AutoDL</li>
      </ul>
      <h3>AI技术</h3>
      <ul>
        <li>计算机视觉 (YOLO, CLIP)</li>
        <li>Transformer与视觉Transformer (ViT)</li>
        <li>强化学习</li>
        <li>自然语言处理 / OpenVLA</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>学术背景</h3>
      <ul>
        <li>深度学习</li>
        <li>概率论</li>
        <li>线性代数</li>
        <li>最优化算法</li>
        <li>启发式算法</li>
        <li>机器学习</li>
      </ul>
      <h3>工具与软件</h3>
      <ul>
        <li>数据分析与可视化</li>
        <li>学术写作与研究</li>
        <li>Webots仿真平台</li>
      </ul>
    </td>
  </tr>
</table>

## 🏆 项目与研究经历

<table>
  <tr>
    <td>
      <div>
        <img src="https://img.shields.io/badge/2024-医学影像-00A170?style=for-the-badge" />
      </div>
    </td>
  </tr>
</table>

<details>
<summary>🔍 <b>基于记忆增强的医学影像分类与报告生成联合优化系统</b> (2024.9-2024.11)</summary>
<br>
在本次研究中担任算法见习以及数据处理和文献查阅职责，针对医学图像分类与报告生成的跨任务协同问题进行研究与系统实现。通过创新性地引入记忆增强机制，实现了分类与报告生成任务的端到端优化。

**核心技术与成果:**
- 针对医学影像数据标签分布不均衡问题，设计了基于动态记忆库的特征学习架构
- 通过构建病理相似度驱动的检索机制，结合多尺度特征金字塔网络，显著提升模型对局部细微病变的识别能力，分类准确率较基线提升12%
- 基于临床专家眼动数据，提出注意力引导的多粒度特征提取策略
- 通过自适应特征融合模块和跨模态知识蒸馏机制，实现了分类任务对报告生成的有效指导，使报告生成的BLEU评分提高15%
- 为解决记忆检索效率问题，改进了基于置信度的动态更新算法，利用层次化索引结构，将检索时间降低40%，同时保证了模型100轮迭代内收敛至损失值0.0015

**技术栈:** PyTorch, Transformers, 医学影像处理, NLP, 多模态学习
</details>

<table>
  <tr>
    <td>
      <div>
        <img src="https://img.shields.io/badge/2024-时序预测-4169E1?style=for-the-badge" />
      </div>
    </td>
  </tr>
</table>

<details>
<summary>🌊 <b>极端天气下的水文时间序列预测模型研究</b> (2024.05-2024.07)</summary>
<br>
基于全国大学生数学建模竞赛研究成果，针对工业级水文传感数据在极端降雨事件预测中的局限性，提出改进型多模态PELT（Polar-Extreme Learning Time-series）预测模型。

**核心技术与成果:**
- 该模型借鉴AAAI'24极端自适应框架，融合极地坐标表征与多端序列建模
- 创新性地结合极地坐标系特征表示方法，提高模型对异常峰值的敏感度
- 设计了针对极端值的特殊损失函数，平衡常规数据与极端数据的学习
- 在八个公开水文数据集上取得显著效果，特别是在极端降雨事件预测中表现优异

**技术栈:** 时间序列分析, 深度学习, 统计建模, Python, 数据可视化
</details>

<table>
  <tr>
    <td>
      <div>
        <img src="https://img.shields.io/badge/2024-多模态学习-FF6B6B?style=for-the-badge" />
      </div>
    </td>
  </tr>
</table>

<details>
<summary>🔄 <b>基于特征融合的图文检索多模态模型项目</b> (2024.03-2024.05)</summary>
<br>
针对互联网内容安全审核中的人工成本问题，设计了一套基于改进CLIP的多模态内容识别系统。

**核心技术与成果:**
- 通过跨模态特征融合机制，突破了原CLIP模型在中文场景下的局限性和22词对的输入限制
- 采用了基于聚类和PCA降维的相似度矩阵优化策略，实现了图-文语义空间的高效对齐
- 引入适配中文语义(SFT)提问的预训练策略，显著提升模型在中文图文理解任务上的表现
- 经过优化后的模型在识别准确率从54%提升至91%，为目标客户为内容审核项目提供了有效可靠的技术方案

**技术栈:** CLIP, 多模态学习, 特征融合, NLP, PyTorch, 交叉注意力机制
</details>

<table>
  <tr>
    <td>
      <div>
        <img src="https://img.shields.io/badge/2023-计算机视觉-28A745?style=for-the-badge" />
      </div>
    </td>
  </tr>
</table>

<details>
<summary>👤 <b>基于深度学习的人脸识别校园应用系统优化</b> (2023.01-2023.03)</summary>
<br>
本人在项目中作为算法工程师（见习），针对校园场景下设备成像质量受限的问题，设计了基于监督学习的多尺度特征提取网络。

**核心技术与成果:**
- 引入位置感知编码（Positional Encoding），增强空间信息的保留
- 提出人脸特征与自适应哈希编码的双流融合架构，显著增强了模型对空间信息的感知能力
- 通过改进的Transformer解码器结构和自注意力机制，实现了人脸特征的高效解码
- 最终使模型识别准确率较基准提升10%，仅需20周期迭代即可将损失值降至0.0048
- 有效解决校园场景下人脸图像采取质量不稳定的问题，提高了实际应用环境中的识别可靠性

**技术栈:** 深度学习, 计算机视觉, Transformer, PyTorch, 哈希编码
</details>

<table>
  <tr>
    <td>
      <div>
        <img src="https://img.shields.io/badge/在研-强化学习-FFA500?style=for-the-badge" />
      </div>
    </td>
  </tr>
</table>

<details>
<summary>🎮 <b>自动化阴阳师策略游戏的强化学习</b></summary>
<br>
主导开发面向回合制策略游戏的智能agent代理系统。针对游戏中速度机制与技能序列决策的复杂性问题，创新地设计了基于多智能体强化学习的决策框架。

**核心技术与成果:**
- 通过引入分层时序差分学习HTL策略，实现战斗节奏控制与技能释放的协同优化
- 基于改进的Transformer架构设计了动态权重注意力机制，有效提升其模型对战局关键信息的感知能力
- 提出双重优化目标训练方案，将速度条动态预测与团队收益最大化相结合，增强了系统在多式神协同对战中的决策水平
- 最终系统在标准对战环境中胜率达到55%，且在复杂策略（如一速流、后手反击等）场景下展现出优秀的适应能力
- 单局对战时间平均缩短30%，大幅提高了游戏自动化的效率

**技术栈:** 强化学习, 多智能体系统, Transformers, PyTorch, 决策树
</details>

<details>
<summary>🎯 <b>基于强化学习的360°具身智能目标追踪系统</b> (在研)</summary>
<br>
设计了基于PPO算法的端到端具身智能训练框架，探索机器人感知与控制的协同优化。

**当前进展:**
- 通过集成YOLOv5(可扩展)目标检测与深度估计CNN网络，实现了50m范围内10-1000个动态目标的实时追踪定位
- 基于Transformer特征提取与优先经验回放的分层强化学习架构，提高复杂环境下的决策稳定性
- 采用课程学习策略使目标命中率提升30%，从简单场景逐步过渡到复杂环境
- 目前正在Webots机器人仿真平台上进行系统验证与优化，重点探索多智能体协同决策、动态场景自适应等方向
- 平均检测精度acc达93.5%，在复杂背景和光照条件下仍保持高精度

**技术栈:** 强化学习, YOLOv5, Transformers, Webots, PPO, CNN, 课程学习
</details>

<table>
  <tr>
    <td>
      <div>
        <img src="https://img.shields.io/badge/2023--2024-校园经历-8E44AD?style=for-the-badge" />
      </div>
    </td>
  </tr>
</table>

<details>
<summary>🏫 <b>校园学术与组织经历</b> (2023.9-2024.07)</summary>
<br>

**数学建模协会会长:**
- 任职校数学建模协会会长，主导承办两届大型数模竞赛
- 统筹赛事组织、协办单位洽谈及财务管理等工作
- 建立健全社团内部管理制度，促进跨院系学术交流

**教学与培训:**
- 担任2024年全国大学生数学建模竞赛校内培训助教
- 负责Python编程实战指导与历年典型赛题分析
- 培训规模累计500+人，显著提升了参赛队伍的技术水平

**学生工作:**
- 同期兼任院学生会部门负责人，协调统筹日常事务
- 策划并组织多次校园学术交流活动，促进跨专业知识共享

</details>

## 🏅 竞赛与奖项

<div align="center">

| 年份 | 竞赛/奖项名称 | 级别 |
|------|--------------|------|
| 2024 | 美国大学生数学建模竞赛 (MCM) | M奖（国际级） |
| 2024 | 全国大学生数学建模竞赛赛后研究 | 获选优秀报告 |
| 2024 | 全国大学生数学建模大赛 | 重庆赛区一等奖 |
| 2024 | 阿里巴巴天池大赛 Lora 文生图挑战赛 | 全国第101名 |
| 2024 | 华数杯全国大学生数学建模竞赛 | 全国一等奖 |
| 2024 | 妈妈杯数学应用比赛 | 重庆市二等奖 |
| 2024 | 国家励志奖学金 | 国家级 |
| 2024 | 星火大模型驱动阅读理解题库构建挑战赛 | 全国第116名 |
| 2024 | 川渝大学生人工智能大赛暨腾讯开悟AI全球公开赛 | 选拔赛第38名，终榜第86名 |
| 2023 | 亚太杯国际数学建模竞赛 | 本科组全国三等奖 |
| 2023 | 中教杯数学建模比赛 | 全国一等奖 |
| 2023 | 数维杯数学建模大学生夏令营 | 优秀营员 |
| 2023 | 天府杯大学生数学建模竞赛 | 全国三等奖 |
| 2023 | 全国大学生数学建模大赛 | 重庆赛区一等奖 |

</div>

<div align="center">
  <img src="https://img.shields.io/badge/数学建模-10+奖项-blue?style=for-the-badge&logo=mathworks&logoColor=white" alt="数学建模奖项" />
  <img src="https://img.shields.io/badge/AI竞赛-多项成就-ff69b4?style=for-the-badge&logo=tensorflow&logoColor=white" alt="AI竞赛奖项" />
</div>

## 📊 GitHub活动与技能统计

<!-- 技能统计 -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chenyinya&layout=compact&theme=radical" alt="使用最多的语言" />
</div>

<!-- GitHub活动图 -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=chenyinya&theme=react-dark&hide_border=true&radius=8" width="100%"/>

<!-- 贡献蛇图 -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chenyinya/chenyinya/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/chenyinya/chenyinya/output/github-contribution-grid-snake.svg">
  <img alt="github贡献图蛇" src="https://raw.githubusercontent.com/chenyinya/chenyinya/output/github-contribution-grid-snake.svg">
</picture>

### 📚 数学建模与AI比赛历程

<div align="center">

| 年份 | 竞赛名称 | 成绩 |
|------|----------|------|
| **2024** | 美国大学生数学建模竞赛 (MCM) | M奖（国际级） |
| **2024** | 全国大学生数学建模竞赛赛后研究 | 获选优秀报告 |
| **2024** | 全国大学生数学建模大赛 | 重庆赛区一等奖 |
| **2024** | 阿里巴巴天池大赛 Lora 文生图挑战赛 | 全国第101名 |
| **2024** | 华数杯全国大学生数学建模竞赛 | 全国一等奖 |
| **2024** | 妈妈杯数学应用比赛 | 重庆市二等奖 |
| **2024** | 川渝大学生人工智能大赛暨腾讯开悟AI全球公开赛 | 选拔赛第38名，终榜第86名 |
| **2023** | 亚太杯国际数学建模竞赛 | 本科组全国三等奖 |
| **2023** | 中教杯数学建模比赛 | 全国一等奖 |
| **2023** | 数维杯数学建模大学生夏令营 | 优秀营员 |
| **2023** | 天府杯大学生数学建模竞赛 | 全国三等奖 |
| **2023** | 全国大学生数学建模大赛 | 重庆赛区一等奖 |

</div>

## 🔄 正在学习

<div align="center">
  <img src="https://img.shields.io/badge/大规模语言模型-学习中-E10098?style=for-the-badge&logo=huggingface&logoColor=white" alt="LLM学习中" />
  <img src="https://img.shields.io/badge/医学多模态融合-探索中-3A1AB6?style=for-the-badge&logo=health&logoColor=white" alt="医学多模态" />
  <img src="https://img.shields.io/badge/强化学习理论-深入研究-FF9900?style=for-the-badge&logo=tensorflow&logoColor=white" alt="强化学习理论" />
  <img src="https://img.shields.io/badge/Diffusion模型-应用实践-9146FF?style=for-the-badge&logo=openai&logoColor=white" alt="Diffusion模型" />
</div>

## 🤝 联系方式

我目前专注于具身智能和医学影像研究 - 热烈欢迎学术合作与技术交流！

<div align="center">
  
[![Email](https://img.shields.io/badge/邮箱-联系-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chenyinya@example.com)
[![WeChat](https://img.shields.io/badge/微信-添加-07C160?style=for-the-badge&logo=wechat&logoColor=white)](https://weixin.qq.com/)
[![知乎](https://img.shields.io/badge/知乎-关注-0084FF?style=for-the-badge&logo=zhihu&logoColor=white)](https://www.zhihu.com/)
[![CSDN](https://img.shields.io/badge/CSDN-博客-CD0000?style=for-the-badge&logo=c&logoColor=white)](https://www.csdn.net/)

</div>

## 💭 座右铭

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="名言" />
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=chenyinya&color=blueviolet&style=for-the-badge" alt="访问统计" />
  <br><br>
  
  <table>
    <tr>
      <td align="center">
        <img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="用爱构建" />
      </td>
      <td align="center">
        <img src="https://forthebadge.com/images/badges/powered-by-coffee.svg" alt="咖啡驱动" />
      </td>
    </tr>
  </table>
  
  <i>🌟 白天是数学建模专家，晚上是AI研究员 🌟</i><br>
  <i>「数据驱动创新，算法改变世界」</i>
</div>
