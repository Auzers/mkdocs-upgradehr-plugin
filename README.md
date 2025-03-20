# MkDocs HR Plugin

一个用于在 MkDocs 中创建带样式分隔线的插件。可以将 `---文字---` 格式的文本转换为带有居中文字的分隔线，并在目录中优雅显示。

[![PyPI version](https://badge.fury.io/py/mkdocs-hr-plugin.svg)](https://badge.fury.io/py/mkdocs-hr-plugin)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## ✨ 特性

- 将 `---文字---` 格式转换为带样式的分隔线
- 在目录中以加粗居中的方式显示分隔线文字
- 自动适配亮色/暗色主题
- 分隔线样式美观，粗细和间距适中
- 简单易用，无需配置

## 🚀 安装

```bash
pip install mkdocs-hr-plugin
```

## 📖 使用方法

在mkdocs.yml中启用插件

```yaml
plugins:
  - hr
```

**示例**
```
- 神经网络
	- 适用于任意类型的数据
	- 训练周期长
	- 适用于迁移学习
	- 容易组合使用

---无监督学习--- # 分隔线

## 1 K-Means

- 建立直觉：K-Means 是一种用**聚类**的算法，将数据集划分为 K 个簇，使同簇数据点更相似，不同簇的数据点差异更大。

其成本函数：

$$
J = \sum_{k=1}^{K} \sum_{x_i \in C_k} \| x_i - \mu_k \|^2
$$

```



## 🎨 效果展示

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
  <div style="text-align: center; margin: 10px;">
    <p><strong>正文</strong></p>
    <img src="https://cdn.jsdelivr.net/gh/Auzers/drawingbed/image/20250320110448217.png" 
         style="height: 300px; 
                width: auto; 
                border-radius: 6px; 
                box-shadow: 0 2px 6px rgba(0,0,0,0.1);" 
         alt="正文">
  </div>

  <div style="text-align: center; margin: 10px;">
    <p><strong>目录</strong></p>
    <img src="https://cdn.jsdelivr.net/gh/Auzers/drawingbed/image/20250320122637910.png" 
         style="height: 300px; 
                width: auto; 
                border-radius: 6px; 
                box-shadow: 0 2px 6px rgba(0,0,0,0.1);" 
         alt="目录">
  </div>
</div>

## 🔧 配置选项

目前插件不需要任何配置，开箱即用。未来可能会添加以下配置选项：
- 自定义分隔线样式
- 自定义文字样式
- 更多主题适配

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📝 更新日志

### 0.1.0 (2024-03-20)
- 初始版本发布
- 基本功能实现

## 📄 许可证

本项目基于 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🙏 致谢

- MkDocs 团队提供的优秀文档工具
- 所有贡献者和用户

## 📮 联系方式

- 作者：amaranth
- 邮箱：amaranth2082@gmail.com
- GitHub：[Auzers](https://github.com/Auzers)

## ⭐ 支持项目

如果这个项目对你有帮助，欢迎star 