# Blank Dataset Website Template

这是一个可直接部署到 GitHub Pages 的科研数据集主页空白模板。

## 页面结构

模板按参考页面的信息结构依次包含：

1. Title / Authors / Affiliations / Project Links
2. Abstract
3. System Overview
4. Dataset
5. Scenarios
6. Data format
7. Download
8. Data Sequences
   - Standard Trajectories
   - Co-captured Trajectories
9. Online Benchmark
10. Citation

所有需要替换的文字都使用 `[PLACEHOLDER]` 标记。

## 使用方法

1. 修改 `index.html` 中所有 `[PLACEHOLDER]` 内容。
2. 用你自己的图片替换 `assets/` 中对应的 SVG 占位图。
3. 修改 Paper / arXiv / Code / Download 等链接。
4. 将整个目录上传到 GitHub 仓库。
5. 在 GitHub 仓库进入 `Settings → Pages`。
6. Source 选择 `Deploy from a branch`。
7. Branch 选择 `main`，目录选择 `/ (root)`。
8. 保存后访问 `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`。

## 图片替换

你可以保留文件名直接覆盖：

- `system-overview.svg`
- `time-synchronization.svg`
- `ground-truth.svg`
- `dataset-feature-1.svg`
- `dataset-feature-2.svg`
- `scenario-01.svg` ~ `scenario-08.svg`
- `ros-topics.svg`
- `trajectory-01.svg` ~ `trajectory-06.svg`

也可以修改 `index.html` 中的 `src` 路径使用 JPG / PNG / WebP。

## 注意

本模板复刻的是参考项目页的栏目顺序与科研数据集信息架构，并使用重新编写的 HTML/CSS 和空白占位内容。
