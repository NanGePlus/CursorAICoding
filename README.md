# 零基础上手 OpenClaw 实战：从零打造智能体驱动的商业自动化闭环

## 本系列视频定位

会先帮助大家建立对 OpenClaw **自托管 Gateway** 的整体认识，接着完成**环境准备、安装部署、飞书接入**，再用 **工作区 Markdown** 固化人设与记忆，最后通过**资讯简报、公众号采集、对话装 Skill** 三个场景完成能力跑通。后续还会持续更新，让大家在能力跑通之后也能获得最新内容。

### 本系列仓库位置

以下仓库存储我在YouTube频道和B站频道关于零基础上手 OpenClaw 实战相关分享所有源文件，均开源免费  

- GitHub地址: [https://github.com/NanGePlus/OpenClawTutorial](https://github.com/NanGePlus/OpenClawTutorial)
- Gitee地址: [https://gitee.com/NanGePlus/OpenClawTutorial](https://gitee.com/NanGePlus/OpenClawTutorial)

### 我的个人信息

- YouTube频道(@南哥AGI研习社)：[https://www.youtube.com/channel/UChKJGiX5ddrIpJG-rBNVZ5g](https://www.youtube.com/channel/UChKJGiX5ddrIpJG-rBNVZ5g)
- B站频道(@南哥AGI研习社)：[https://space.bilibili.com/509246474](https://space.bilibili.com/509246474)
- GitHub地址：[https://github.com/NanGePlus](https://github.com/NanGePlus)
- Gitee地址：[https://gitee.com/NanGePlus](https://gitee.com/NanGePlus)
- 大模型代理平台: [https://nangeai.top/](https://nangeai.top/)

### 其他开源分享推荐

- **LangChain系列**：最新V1.x版本全家桶LangChain+LangGraph+DeepAgents  
B站视频链接：[https://www.bilibili.com/video/BV17c6mBbEHv/](https://www.bilibili.com/video/BV17c6mBbEHv/)
YouTube视频链接：[https://www.youtube.com/playlist?list=PL8zBXedQ0ufld2C7nB28fGw9U6nTbagp1](https://www.youtube.com/playlist?list=PL8zBXedQ0ufld2C7nB28fGw9U6nTbagp1)
GitHub地址：[https://github.com/NanGePlus/LangChain_V1_Test](https://github.com/NanGePlus/LangChain_V1_Test)  
Gitee地址：[https://gitee.com/NanGePlus/LangChain_V1_Test](https://gitee.com/NanGePlus/LangChain_V1_Test)
- **n8n系列**：最新n8n自动化工作流平台
B站视频链接：[https://www.bilibili.com/video/BV1Aq1NBYELp/](https://www.bilibili.com/video/BV1Aq1NBYELp/)
YouTube视频链接：[https://www.youtube.com/playlist?list=PL8zBXedQ0uflhkZBwlQNAp7H57CJFgfgV](https://www.youtube.com/playlist?list=PL8zBXedQ0uflhkZBwlQNAp7H57CJFgfgV)  
GitHub地址：[https://github.com/NanGePlus/N8NWorkflowsTest](https://github.com/NanGePlus/N8NWorkflowsTest)
Gitee地址：[https://gitee.com/NanGePlus/N8NWorkflowsTest](https://gitee.com/NanGePlus/N8NWorkflowsTest)                
- **Cursor系列**：专为提升开发生产力而设计的一款AI提效工具
B站视频链接：[https://www.bilibili.com/video/BV1HEABzvEdo/](https://www.bilibili.com/video/BV1HEABzvEdo/)
YouTube视频链接：[https://www.youtube.com/playlist?list=PL8zBXedQ0ufkcPJWHVKFTFzS8yNCkfM5b](https://www.youtube.com/playlist?list=PL8zBXedQ0ufkcPJWHVKFTFzS8yNCkfM5b)
GitHub地址：[https://github.com/NanGePlus/CursorAICoding](https://github.com/NanGePlus/CursorAICoding)  
Gitee地址：[https://gitee.com/NanGePlus/CursorAICoding](https://gitee.com/NanGePlus/CursorAICoding)   
- **更多开源项目**
GitHub地址：[https://github.com/NanGePlus](https://github.com/NanGePlus)
Gitee地址：[https://gitee.com/NanGePlus](https://gitee.com/NanGePlus)

---

## 适合的小伙伴

- 希望用 **飞书（含 Lark，其他也类似）** 作为入口，驱动 **带工具与记忆的智能体** 的开发者、运营与重度个人用户。  
- 已具备基础 AI 对话能力，愿意按后续文档完成 **Node 环境、API Key、插件配置** 等的动手型小伙伴。  
- 能接受「先跑通再优化」：先让 Gateway 与飞书绿通，再迭代工作区与定时任务，最后渐进式迭代。



