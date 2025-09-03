# Electrochemistry + AI Project（公开）

目标：基于公开数据研究电池健康（SOH / RUL）并公开 Demo、结果与论文摘要。  
详细实验、原始数据与大型文件保存在私有仓库 `electrochem-ai-private`。

结构：
- `docs/`：项目文档（数据说明、方法、结果）
- `demo/`：最小可行 Demo（前端 + 后端）
- `figures/`：可公开的图表

electrochem-ai-project/
├── docs/ # 项目文档，自动生成静态站点
│ ├── index.md # 首页
│ ├── data_overview.md # 数据说明
│ ├── methods.md # 方法与模型
│ └── demo.md # Demo 说明
├── demo/ # 前端或后端最小可行示例
├── figures/ # 可公开的图表、可视化结果
├── notebooks/ # 公共实验 Notebook（不含敏感数据）
├── src/ # 实用工具脚本
├── mkdocs.yml # MkDocs 配置
└── .github/workflows/ # 自动化部署脚本