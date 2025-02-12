# Prompt  
AI 指令合集 - 开放协作的知识仓库  
[![CC0 License](https://img.shields.io/badge/license-CC0-green.svg)](https://creativecommons.org/publicdomain/zero/1.0/)  
我不是知识的创造者，只是互联网上的搬运工。欢迎通过 PR 贡献你的 Prompt 魔法！



### 贡献方式 ✨

1. **提交新指令**  
   - 在对应分类的 Markdown 文件中添加内容（格式见下方模板）
   - 若需新建分类，请先在 [Discussion](链接) 发起讨论
   - 提交 Pull Request 并描述指令用途

2. **完善现有内容**  
   - 修正错误指令
   - 补充使用场景说明
   - 优化指令结构（添加参数说明/示例）

3. **社区协作**  
   - 参与 PR Review
   - 在 Issues 中标注需要优化的指令
   - 帮助整理重复/失效内容



### 分类指南 🗂️

我们采用 **场景化分类法**，当前主要类别：

| 分类图标 | 主类                | 子类                  | 具体场景                                                                 | 示例 Prompt                                 |
|----------|---------------------|-----------------------|--------------------------------------------------------------------------|--------------------------------------------|
| 📌       | **效率工具类**      | 办公自动化            | 邮件处理/会议记录/日程管理                                              | "将会议录音转换为结构化待办事项"           |
|          |                     | 编程开发              | 代码生成/调试辅助/文档编写                                               | "为{{编程语言}}函数添加类型注解"           |
|          |                     | 数据分析              | 报表生成/趋势预测/数据清洗                                               | "将 CSV 数据可视化为{{图表类型}}报告"      |
|          |                     | 知识管理        | 信息归档/知识图谱构建/速查手册                                           | "将零散笔记整理为 Q&A 知识库"              |
| 🎨       | **创意创作类**      | 文案生产              | 广告词/社交媒体/营销文案                                                 | "生成{{节日}}主题朋友圈九宫格文案"         |
|          |                     | 视觉设计              | Logo设计/配色方案/UI原型                                                 | "为{{行业}}APP设计极简风格图标集"          |
|          |                     | 故事创作              | 小说大纲/角色设定/世界观构建                                             | "生成科幻题材的三幕剧情节模板"             |
|          |                     | 多媒体制作      | 视频脚本/播客提纲/分镜设计                                               | "编写{{产品}}开箱视频的运镜指令"           |
| 🔬       | **学术研究类**      | 论文写作              | 文献综述/方法论描述/摘要优化                                             | "将实验数据转化为图表说明段落"             |
|          |                     | 实验设计              | 变量控制/流程规划/伦理审查                                               | "生成生物实验的阴性对照组设置方案"         |
|          |                     | 学术交流              | 会议报告/答辩讲稿/审稿意见                                               | "将论文结论转换为10分钟学术演讲大纲"       |
|          |                     | 跨学科研究      | 方法论迁移/术语对照/协作框架                                             | "建立计算机视觉与医学影像的术语映射表"     |
| 🌐       | **语言处理类**      | 多语言互译            | 专业文档翻译/文化适配转换                                                | "将中文成语转化为英文惯用表达"             |
|          |                     | 文本优化              | 风格转换/语法修正/情感调整                                               | "将技术文档改写为初中生可读版本"           |
|          |                     | 语音交互              | 对话设计/语音指令/播客剪辑                                               | "生成智能家居设备的自然对话流程图"         |
|          |                     | 方言保护        | 方言转写/濒危语言留存/地方文化传承                                        | "将闽南语童谣转换为拼音注音版本"           |
| 🧠       | **思维训练类**      | 决策支持              | SWOT分析/风险评估/优先级排序                                             | "制定新产品上市的决策树模型"               |
|          |                     | 批判性思维            | 逻辑谬误检测/观点辩证/信息溯源                                           | "识别新闻报道中的统计偏差"                 |
|          |                     | 创意激发              | 头脑风暴/逆向思维/跨界联想                                               | "用生物进化论解构社交媒体传播模式"         |
|          |                     | 认知提升 (NEW)        | 记忆训练/专注力培养/元认知开发                                           | "设计基于遗忘曲线的单词记忆方案"           |
| 🏗️       | **工程应用类** | 产品设计              | 需求分析/原型测试/用户反馈处理                                           | "将用户访谈整理为功能优先级矩阵"           |
|          |                     | 流程优化              | 自动化节点设计/异常处理方案                                              | "优化电商客服对话的意图识别路径"           |
|          |                     | 技术文档              | API文档/操作手册/故障排查指南                                            | "生成 Docker 容器的常见报错解决方案"       |
| 🌱       | **可持续发展类** | 绿色计算            | 碳足迹估算/能效优化方案                                                  | "评估算法训练的环境成本改进策略"           |
|          |                     | 社会责任              | 伦理审查框架/普惠技术方案                                                | "设计视障用户友好的语音交互系统"           |



### 格式规范 📝

请按此模板提交（Markdown 格式）：

```markdown
#### 精准翻译模式

- prompt:

​```prompt
你的具体指令（建议包含变量占位符如 {{参数}}）
​```

- params: 

​```params
参数1: 说明
参数2: 说明
​```

- scene: 使用场景说明
- source: 来源（可选）
- author: 你的GitHub ID
- version: 2023.08.07
```

示例：

```markdown
#### 精准翻译模式

- prompt:

​```prompt
/开启专业翻译模式 
【源语⾔】中⽂ 
【⽬标语⾔】商务英语 
【特殊要求】 
- 保留敬语格式（Dear/Honored） 
- ⾦额保留两位⼩数 
- 使⽤ICC国际商会术语
​```

- scene: 商务翻译使用
- source: 来源（可选）
- author: AI搬运工
- version: 2023.08.07
```



### 协作公约 🤝

1. 所有贡献默认采用 [CC0 协议](https://creativecommons.org/publicdomain/zero/1.0/)
2. 请确保指令经过实际验证
3. 禁止提交含个人隐私/商业机密内容
4. 新增分类需获得 3 位以上协作者认可



### 进阶贡献者 🏆
连续 3 次有效贡献者可申请成为：
- **分类维护者**：负责特定类别的质量审核
- **翻译专员**：协助多语言版本建设
- **模版设计师**：优化指令结构化模版

> 项目路线图 & 待办事项见 [PROJECT.md](链接)  
> 交流讨论请至 [Discussion](链接) 板块

