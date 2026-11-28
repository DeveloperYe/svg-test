# 苯丙氨酸分子结构演示

使用 Three.js 构建的苯丙氨酸交互式 3D 分子页面，展示完整分子骨架、元素颜色、分子性质和关键官能团。支持拖动旋转、滚轮缩放、原子点击检查，以及自动旋转、原子标签和氢原子显示切换。

## 运行

在项目目录启动一个静态 HTTP 服务：

```bash
python3 -m http.server 8000
```

访问 <http://localhost:8000>。Three.js 与 OrbitControls 从 jsDelivr CDN 加载，因此运行时需要网络连接。
