# 🎨 GaG Receitas BR - 图片需求清单

## 📋 必需图片列表

### 1. Open Graph 社交媒体图片 (1200x630px)

#### `og-home.jpg` - 首页社交分享图
**设计要求:**
- 尺寸: 1200x630px
- 主色调: 渐变紫色 (#667eea 到 #764ba2)
- 内容要素:
  - 🌱 GaG Receitas BR logo
  - "Guia Completo Grow a Garden"
  - "25.000+ Jogadores Brasileiros"
  - Roblox风格的烹饪图标
  - 巴西国旗小元素

#### `og-recipes.jpg` - 食谱页面图
**设计要求:**
- 尺寸: 1200x630px
- 主色调: 食物主题暖色调
- 内容要素:
  - "150+ Receitas Testadas"
  - 各种食谱图标 (🔮💎🌟⚡)
  - "Prismatic • Transcendent • Rápidas"
  - 烹饪锅和食材插画

#### `og-calculator.jpg` - 计算器页面图
**设计要求:**
- 尺寸: 1200x630px
- 主色调: 科技蓝色调
- 内容要素:
  - 🧮 计算器图标
  - "Calculadora de Lucros"
  - 图表和数据可视化元素
  - "Otimize seus Sheckles"

#### `og-faq.jpg` - FAQ页面图
**设计要求:**
- 尺寸: 1200x630px
- 主色调: 友好的绿色调
- 内容要素:
  - ❓ FAQ图标
  - "Perguntas Frequentes"
  - 问答气泡图形
  - "Suporte 24/7"

#### `og-about.jpg` - 关于我们页面图
**设计要求:**
- 尺寸: 1200x630px
- 主色调: 团队主题色彩
- 内容要素:
  - 🇧🇷 巴西元素
  - "Equipe GaG Receitas BR"
  - 团队协作图标
  - "Comunidade Brasileira"

### 2. Logo和品牌元素

#### `logo.png` - 主要Logo
**设计要求:**
- 尺寸: 200x200px (方形)
- 格式: PNG透明背景
- 设计元素:
  - 🌱 植物/花园主题
  - 现代简洁设计
  - 可读性强的字体
  - 适合深色和浅色背景

#### `favicon.ico` - 网站图标
**设计要求:**
- 尺寸: 32x32px, 16x16px多尺寸
- 格式: ICO
- 简化版logo，在小尺寸下清晰可见

### 3. 装饰性图片 (可选但推荐)

#### `hero-bg.jpg` - 首页背景图
**设计要求:**
- 尺寸: 1920x1080px
- 主题: Roblox Grow a Garden游戏场景
- 风格: 明亮、吸引人
- 与渐变叠加效果兼容

#### `recipe-icons/` - 食谱图标集
**设计要求:**
- 尺寸: 64x64px每个
- 格式: PNG透明背景
- 图标列表:
  - `prismatic-icon.png` - 水晶/钻石主题
  - `transcendent-icon.png` - 星星/光芒主题
  - `fast-icon.png` - 闪电/速度主题
  - `efficient-icon.png` - 齿轮/优化主题

## 🎨 设计风格指南

### 颜色方案
```css
主色调: #6a5acd (SlateBlue)
次要色: #667eea (蓝紫色)
强调色: #764ba2 (深紫色)
成功色: #28a745 (绿色)
警告色: #ffc107 (黄色)
```

### 字体建议
- **主标题**: Roboto Bold / Montserrat Bold
- **副标题**: Roboto Medium
- **正文**: Roboto Regular

### 设计风格
- **现代扁平设计**
- **圆角元素** (15px border-radius)
- **柔和阴影**
- **渐变背景**
- **巴西文化元素**

## 📐 技术规格

### Open Graph图片优化
- **文件大小**: < 300KB每张
- **格式**: JPG (照片) 或 PNG (图形)
- **压缩**: 85%质量
- **色彩空间**: sRGB

### Logo规格
- **矢量格式**: SVG (用于缩放)
- **位图格式**: PNG (透明背景)
- **最小尺寸**: 32x32px仍需清晰
- **最大尺寸**: 512x512px

## 🛠️ 创建工具推荐

### 免费工具
1. **Canva** - 社交媒体图片模板
2. **GIMP** - 免费图像编辑
3. **Figma** - UI设计和图标
4. **Unsplash** - 免费背景图片

### 付费工具
1. **Adobe Photoshop** - 专业图像编辑
2. **Adobe Illustrator** - 矢量图形
3. **Sketch** - UI设计
4. **Affinity Designer** - 经济型设计软件

## 📝 图片文件命名规范

```
/image/
├── og-home.jpg          (1200x630)
├── og-recipes.jpg       (1200x630)
├── og-calculator.jpg    (1200x630)
├── og-faq.jpg          (1200x630)
├── og-about.jpg        (1200x630)
├── logo.png            (200x200)
├── logo.svg            (矢量)
├── favicon.ico         (多尺寸)
├── hero-bg.jpg         (1920x1080)
└── icons/
    ├── prismatic.png   (64x64)
    ├── transcendent.png (64x64)
    ├── fast.png        (64x64)
    └── efficient.png   (64x64)
```

## ✅ 图片优化检查清单

- [ ] 所有Open Graph图片都是1200x630px
- [ ] 文件大小都小于300KB
- [ ] Logo在不同背景下都清晰可见
- [ ] Favicon在浏览器标签页中清晰
- [ ] 图片包含适当的Alt文本信息
- [ ] 颜色与网站主题保持一致
- [ ] 所有图片都经过压缩优化
- [ ] 支持高分辨率显示设备

## 🎯 内容建议

### Open Graph图片文字内容
- **简洁明了** - 最多3-4个关键词
- **品牌一致性** - 使用相同字体和颜色
- **可读性** - 在小尺寸下仍然清晰
- **本地化** - 巴西葡萄牙语文本

### 图标设计原则
- **一致性** - 相同的设计风格
- **可识别性** - 即使很小也能识别
- **主题相关** - 与游戏内容相关
- **文化适应** - 适合巴西用户

---

**注意**: 创建这些图片后，请确保将它们上传到 `/image/` 文件夹，并验证所有链接都能正常工作。建议先创建Open Graph图片，因为它们对SEO和社交媒体分享最为重要。

