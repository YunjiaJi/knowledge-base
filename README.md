# 个人知识库

当前分为五个板块：
1. 数学与物理基础
2. 计算机与人工智能基础
3. 自动驾驶与研究方法
4. 论文知识库
5. 英语词汇库

## 文件结构
- `index.html`：网页界面、搜索与分类浏览。
- `data/math.json`：数学与物理基础。
- `data/ai.json`：计算机与人工智能基础。
- `data/driving.json`：自动驾驶与研究方法。
- `data/papers.json`：论文卡片。
- `data/english.json`：英语词汇卡片。

## 本地预览
网页通过 fetch 读取 JSON 文件，请在仓库目录运行：
```bash
python -m http.server 8000
```
浏览器访问 `http://localhost:8000`。

这是初步版本，知识卡片会持续补充。Epona 卡片目前是根据已有讨论形成的学习摘要，正式论文信息、原文图表和实验数据仍需逐项核对后补充。
