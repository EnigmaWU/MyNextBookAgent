# 用例故事 (Use Cases)

本文件列出 MyNextBookAgent 核心功能 Top-3 用例，中英文对照，包含 SAVE、NEXT、RECALL、REPORT 四大模块。

## SAVE：内容保存 (Content Saving)

### SAVE-US-1：导入与保存新书 (Import & Save Book)
- **AS**: a book reader  
  作为读书人
- **WHEN**: under login and in SAVE module  
  在登录并进入 SAVE 模块时
- **I WANT**: upload or paste book files and notes  
  我希望上传或粘贴图书文件和笔记
- **EXPECT**: them to be saved and visible  
  期望它们被保存并展示
- **SO THAT**: I can manage my readings  
  以便管理我的阅读

### SAVE-US-2：智能分类 (Smart Categorization)
- **AS**: a book manager  
  作为书籍管理者
- **WHEN**: under having multiple saved items  
  在存在多条保存内容时
- **I WANT**: auto-categorize saved content by theme  
  我希望按主题自动分类保存内容
- **EXPECT**: a clear category structure  
  期望生成清晰的分类结构
- **SO THAT**: I can find related content quickly  
  以便快速查找相关内容

### SAVE-US-3：编辑与删除 (Edit & Delete Content)
- **AS**: a content editor  
  作为内容编辑者
- **WHEN**: under having saved items  
  在已有保存内容时
- **I WANT**: edit or delete entries  
  我希望编辑或删除条目
- **EXPECT**: immediate update in list  
  期望列表立即更新
- **SO THAT**: I maintain accurate records  
  以便保持记录准确

## NEXT：书籍推荐 (Book Recommendations)

### NEXT-US-1：基于历史推荐 (Recommend from History)
- **AS**: a book explorer  
  作为书籍探索者
- **WHEN**: under having saved records  
  在有保存记录时
- **I WANT**: run AlgA to generate three recommendations  
  我希望运行 AlgA 算法生成三本推荐
- **EXPECT**: covers, summaries, and reasons  
  期望查看封面、摘要和推荐理由
- **SO THAT**: I discover new books  
  以便发现新书

### NEXT-US-2：再来三本 (More Three)
- **AS**: a recommendation tuner  
  作为推荐调优者
- **WHEN**: under unsatisfied recommendations  
  在当前推荐不满意时
- **I WANT**: click “再来三本”  
  我希望点击“再来三本”
- **EXPECT**: a new set of recommendations  
  期望获得新一组推荐
- **SO THAT**: I find books I like  
  以便找到心仪书籍

### NEXT-US-3：本地优先下载 (Local-First Download)
- **AS**: a resource downloader  
  作为资源下载者
- **WHEN**: under recommendation list availability  
  在推荐列表可用时
- **I WANT**: choose pre-download or instant download  
  我希望选择预下载或立即下载
- **EXPECT**: local files prioritized or online EPUB > PDF  
  期望优先使用本地文件或在线 EPUB > PDF
- **SO THAT**: I access books quickly  
  以便快速获取图书

## RECALL：知识回忆 (Knowledge Recall)

### RECALL-US-1：最近回顾 (Recent Review)
- **AS**: a knowledge reviewer  
  作为知识回顾者
- **WHEN**: under having one day of records  
  在有一天记录时
- **I WANT**: view records and add insights  
  我希望查看记录并添加见解
- **EXPECT**: insights attached to records  
  期望见解附加到记录
- **SO THAT**: I enrich past learnings  
  以便丰富对过去阅读的理解

### RECALL-US-2：新增见解 (Add New Insight)
- **AS**: a knowledge enhancer  
  作为知识增强者
- **WHEN**: under having saved records  
  在有保存记录时
- **I WANT**: add new insights to records  
  我希望向记录添加新见解
- **EXPECT**: them to be saved and visible  
  期望它们被保存并展示
- **SO THAT**: I can reflect on my learnings  
  以便反思我的学习

### RECALL-US-3：洞见链接 (Insight Link)
- **AS**: a knowledge seeker  
  作为知识探索者
- **WHEN**: under having saved insights  
  在有保存见解时
- **I WANT**: link my insights to famous thinkers  
  我希望将我的见解链接到著名思想家
- **EXPECT**: a list of related thinkers  
  期望生成相关思想家的列表
- **SO THAT**: I feel connected to great thoughts  
  以便感受到伟大思想的联系

## REPORT：数据报告 (Data Reporting)

### REPORT-US-1：统计可视化 (Statistics Visualization)
- **AS**: a data analyst  
  作为数据分析者
- **WHEN**: under having weekly/monthly/annual records  
  在有周/月/年记录时
- **I WANT**: generate reading and note charts  
  我希望生成阅读和笔记图表
- **EXPECT**: different time range support  
  期望支持不同时间范围
- **SO THAT**: I can easily get my reading statistics  
  以便轻松获取我的阅读统计

### REPORT-US-2：知识图谱 (Knowledge Graph)
- **AS**: a knowledge explorer  
  作为洞见探索者
- **WHEN**: under having saved records  
  在有保存记录时
- **I WANT**: view knowledge graph  
  我希望查看知识图谱
- **EXPECT**: nodes and edges clickable  
  期望节点和连边可点击
- **SO THAT**: I discover connections  
  以便发现思想联系

### REPORT-US-3：主题分析 (Theme Analysis)
- **AS**: a theme analyzer  
  作为主题分析者
- **WHEN**: under having saved records  
  在有保存记录时
- **I WANT**: generate theme distribution chart  
  我希望生成主题分布图
- **EXPECT**: a clear visual representation  
  期望清晰的可视化表示
- **SO THAT**: I understand my reading focus  
  以便了解我的阅读重点
