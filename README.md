# 标准氨基酸分子结构演示

使用 Three.js 构建的 20 种标准蛋白质氨基酸交互式 3D 分子页面，展示分子骨架、元素颜色、分子性质和侧链结构。可通过右侧选择器切换氨基酸，并拖动旋转、滚轮缩放、点击检查原子，或切换自动旋转、原子标签和氢原子显示。

## 运行

在项目目录启动一个静态 HTTP 服务：

```bash
python3 -m http.server 8000
```

访问 <http://localhost:8000>。Three.js 与 OrbitControls 从 jsDelivr CDN 加载，因此运行时需要网络连接。
