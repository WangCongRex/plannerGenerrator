# plannerGenerrator / 月度计划手帐生成器

🌐 **在线地址**: [https://plannergenerrator.pages.dev/](https://plannergenerrator.pages.dev/)

## 🌟 项目简介

基于 **jsPDF** 的静态HTML工具，可直接生成**指定年月的打印级月度计划手帐PDF**。无需配置，打开网页即可使用。

> 特点：极简设计、无外部依赖、生成速度快

![截图](https://github.com/WangCongRex/plannerGenerrator/blob/main/image/screenshot.png)

---

## ✨ 功能说明

* **年月选择**

  通过下拉菜单选择目标年份与月份
* **一键生成PDF**

  点击按钮直接下载打印级精度的月度计划模板
* **固定布局模板**

  内置标准化手帐布局（不可修改格式/主题）

---

## 🚀 使用方式

1. 访问 [https://plannergenerrator.pages.dev/](https://plannergenerrator.pages.dev/)
2. 输入年份与月份
3. 点击 **"生成"** 按钮
4. 自动下载命名格式为 `planner_YYYY_MM.pdf` 的文件

---

## ⚙️ 技术实现

```
graph LR
  A[HTML选择界面] --> B(jsPDF实例化)
  B --> C[生成PDF页面]
  C --> D[自动下载]
```

* **核心库**: jsPDF (v1.5.3)
* 

---

## 📄 项目结构

```
planner-generator/
├── index.html          # 主界面
├── planner-template/   # 手帐HTML模板 
├── js/
│   └── jspdf.min.js    # jsPDF库(v1.5.3)
│   └── MapleMono-CN-Medium-normal.js    # Maple Mono字体
│   └── MapleMono-CN-SemiBold-normal.js    # Maple Mono字体（粗体）
└── assets/             # 静态资源
```

---

## ❓ 常见问题

**Q: 支持自定义手帐样式吗？**

→ 当前版本使用固定模板，不支持修改布局或主题

**Q: 需要安装软件吗？**

→ **不需要**，纯浏览器环境运行

---

## 📜 许可证

MIT License © 2025

完整声明见 [LICENSE](https://github.com/yourname/planner-generator/blob/main/LICENSE)
