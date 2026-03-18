#  autoresearcher自动科研-openclaw MiniMax Coding Plan 实例
## 1. 项目简介
autoresearcher自动科研是一个基于开源工具openclaw的科研辅助工具，是一个自动化学术研究助手，以“搜索→下载→阅读→归档→创新点生成验证“的方式辅助科研。

以Minimax Coding Plan（现在名为Token Plan）的实践为例
您需要提前准备：
- （必须）需要安装openclaw工具，并配置好相关环境。包括但不限于Minimax的非Token式调用。
- （较为劝退）为了使用Minimax的MCP联网搜索功能，我采取的方案是使用一次性对话的方式调用acpx opencode exec技能进行联网搜索。您需要下载安装opencode并配置好Minimax的API密钥。


## 2. 按顺序配置
- **目录设置**。前往PATHS.md设置
- **openclaw项目目录**。默认是~/.openclaw/,如果不是，请在SKILL.md这个核心文档中修改。
- **定时任务工作量**。 在SKILL.md中设置单轮的工作量。酌情增减。可以让openclaw帮你改skill。
- **研究方向**。前往DIRECTIONS.md设置。
- **偏好设置**。前往PREFERENCES.md设置。