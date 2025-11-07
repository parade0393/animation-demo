# CSS Transform & Transition 交互式教程

一个完整的 CSS 动画教程项目，包含详细的文字解释、代码展示和可交互的动画演示。

## 📚 教程内容

### 基础概念

- **坐标系统** - 理解 CSS 中的 X、Y、Z 轴和坐标原点

### Transform 变换

- **translate()** - 2D 平移
- **translateX()** - X 轴平移
- **translateY()** - Y 轴平移
- **rotate()** - 2D 旋转
- **rotateX()** - X 轴 3D 旋转
- **rotateY()** - Y 轴 3D 旋转
- **scale()** - 2D 缩放
- **scaleX()** - X 轴缩放
- **scaleY()** - Y 轴缩放
- **skew()** - 2D 倾斜
- **skewX()** - X 轴倾斜
- **skewY()** - Y 轴倾斜
- **组合变换** - 多个变换的组合使用

### Transition 过渡

- **transition-duration** - 控制动画持续时间
- **transition-timing-function** - 控制动画速度曲线（缓动函数）
- **transition-delay** - 控制动画延迟时间

### 3D 变换

- **perspective** - 透视效果
- **rotate3d()** - 3D 旋转
- **translate3d()** - 3D 平移

## 🚀 使用方法

1. 在浏览器中打开 `index.html` 查看教程目录
2. 点击任意卡片进入对应的演示页面
3. 或者直接打开 `demos/` 文件夹中的任意 HTML 文件
4. 每个演示页面都包含：
   - 详细的概念解释
   - 语法说明
   - 多个交互式示例
   - 可运行的代码展示
   - 实用的应用场景提示

## 📁 项目结构

```
.
├── index.html          # 首页（卡片式教程目录）
├── styles.css          # 共享样式（供所有 demo 页面使用）
├── demos/              # 所有演示页面（共 20 个）
│   ├── coordinate.html      # 坐标系统
│   ├── translate.html       # 2D 平移
│   ├── translateX.html      # X 轴平移
│   ├── translateY.html      # Y 轴平移
│   ├── rotate.html          # 2D 旋转
│   ├── rotateX.html         # X 轴 3D 旋转
│   ├── rotateY.html         # Y 轴 3D 旋转
│   ├── scale.html           # 2D 缩放
│   ├── scaleX.html          # X 轴缩放
│   ├── scaleY.html          # Y 轴缩放
│   ├── skew.html            # 2D 倾斜
│   ├── skewX.html           # X 轴倾斜
│   ├── skewY.html           # Y 轴倾斜
│   ├── multiple.html        # 组合变换
│   ├── duration.html        # 过渡持续时间
│   ├── timing.html          # 缓动函数
│   ├── delay.html           # 过渡延迟
│   ├── perspective.html     # 透视效果
│   ├── rotate3d.html        # 3D 旋转
│   └── translate3d.html     # 3D 平移
└── README.md
```

## ✨ 特性

- 🎨 精美的 UI 设计，渐变色卡片布局
- 📱 响应式布局，适配各种屏幕尺寸
- 🎯 交互式动画演示，点击按钮即可播放
- 💡 实用的代码示例，带语法高亮
- 📖 详细的中文说明，易于理解
- 🎭 每个概念都有 2-3 个不同示例
- 🔄 可重复播放的动画效果
- 🎪 包含 3D 立方体等高级演示
- 🚀 无需构建工具，直接在浏览器中运行

## 🎓 学习建议

1. **从基础开始**：先学习"坐标系统"，理解 X、Y、Z 轴的概念
2. **循序渐进**：按照首页的分类顺序学习（基础概念 → Transform → Transition → 3D）
3. **动手实践**：每个示例都点击"播放动画"按钮，观察实际效果
4. **理解原理**：仔细阅读每个页面的语法说明和参数解释
5. **对比学习**：注意观察相似函数的区别（如 translate vs translateX）
6. **修改尝试**：使用浏览器开发者工具修改代码中的数值，看看效果如何变化
7. **实际应用**：参考"应用场景"提示，思考如何在项目中使用

## 🌟 应用场景

- 按钮悬停效果
- 卡片翻转动画
- 图片画廊
- 产品 3D 展示
- 页面过渡效果
- 加载动画
- 菜单展开/收起
- 工具提示显示

## 📝 技术栈

- HTML5
- CSS3 (Transform, Transition, Animation)
- Vanilla JavaScript

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可

MIT License
