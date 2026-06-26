<p align="center">
<img src="/assets/logo.png" alt="ExpenseOwl Logo" width="200" height="200" /><br>
</p>

<h1 align="center">jizhang · 记账</h1><br>

<p align="center">
基于 <a href="https://github.com/tanq16/expenseowl">ExpenseOwl</a> 的增强分支，自托管简易记账工具。
</p>

<br>

# 新增功能

### 中英文界面切换

支持在设置页面一键切换**中文 / English** 界面，翻译覆盖仪表盘、表格视图、设置页面及所有交互提示。

### 自定义日期范围筛选

饼图原先仅支持按月查看，现新增 **自定义日期范围** 模式，可在月度与任意起止日期之间切换，更灵活地分析特定时段收支。

### 其余改进

- 表单提示、导航 tooltip 等全面汉化
- 日期格式化根据当前语言自适应
- 复用上游全部功能（详见下方完整文档）

---

# 完整文档

安装、使用、配置、数据导入导出、PostgreSQL 后端等完整说明请移步原项目：

👉 [ExpenseOwl — README](https://github.com/tanq16/expenseowl)

核心功能概要：

- 快速记录支出/收入（仅需日期、金额、类别）
- 定期交易（支持收入和支出）
- 自定义类别、货币符号、账单起始日
- 标签分类
- 饼图可视化 + 现金流展示
- 明/暗主题
- CSV 导入/导出
- PWA 支持
- JSON / PostgreSQL 双存储后端
- 单文件二进制 & Docker 容器部署

---

<p align="center">
<a href="https://github.com/tanq16/expenseowl">ExpenseOwl 原项目</a>&nbsp;&bull;&nbsp;<a href="https://github.com/tanq16/expenseowl/blob/main/README.md">完整文档</a>
</p>
