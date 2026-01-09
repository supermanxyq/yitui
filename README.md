# Bootstrap 企业官网模板

这是一个基于 Bootstrap 5 开发的企业官网模板，具有自适应布局，适合各类企业使用。

## 功能特点

- 响应式设计，适配各种屏幕尺寸
- 基于 Bootstrap 5 构建
- 简洁现代的 UI 设计
- 易于定制和扩展
- 包含多个常用企业官网模块

## 文件结构

```
project/
├── index.html        # 网站主页
├── css/
│   └── style.css     # 自定义样式
├── images/           # 图片资源目录
│   ├── logo.png      # 网站logo
│   ├── hero-bg.jpg   # 首页banner背景
│   ├── icon1-8.png   # 功能图标
│   ├── app-mockup.png # APP展示图
│   └── ...           # 其他图片资源
└── README.md         # 项目说明文档
```

## 使用方法

1. 克隆或下载此仓库
2. 在 images 目录中添加所需的图片资源
   - logo.png - 网站 logo
   - hero-bg.jpg - 首页大型 banner 背景图
   - icon1.png ~ icon8.png - 核心业务能力图标
   - app-mockup.png - APP 界面展示图
   - team1.jpg, team2.jpg - 团队成员照片
   - case1.jpg ~ case4.jpg - 案例展示图片
   - tech-diagram.png - 技术架构图
   - qrcode.png - 微信公众号二维码
3. 根据需要修改 index.html 中的内容
4. 在 style.css 中调整样式以满足品牌需求

## 自定义

### 修改颜色主题

在`css/style.css`文件的`:root`部分修改颜色变量：

```css
:root {
  --primary-color: #你的主题色;
  --secondary-color: #次要颜色;
  /* 其他颜色变量 */
}
```

### 替换内容

1. 修改`index.html`中的文本内容
2. 替换`images`目录中的图片资源
3. 根据需要添加或删除网站各部分内容

## 浏览器兼容性

- Chrome (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- Edge (最新版本)
- Opera (最新版本)

## 注意事项

使用前请确保`images`目录中包含所有必要的图片资源，否则页面可能无法正常显示。

# 百付科技官网图片资源清单

## 导航栏

- `images/logo.png` - 公司 Logo

## 轮播图/Banner

- `images/hero-bg.png` - 首页 Banner 背景图 1
- `images/hero-bg2.png` - 首页 Banner 背景图 2
- `images/hero-bg3.png` - 首页 Banner 背景图 3

## 核心业务能力

1. `images/icon1.png` - NFC 获客系统
2. `images/icon2.png` - 团购外卖代运营
3. `images/icon3.png` - 视频号+爆店码
4. `images/icon4.png` - 短视频矩阵营销
5. `images/icon5.png` - AI 赋能直播
6. `images/icon6.png` - AI 数字人短视频
7. `images/icon7.png` - AI 智能客服
8. `images/icon8.png` - 企业 AI 训练模型
9. `images/icon9.png` - AI 智慧一体机
10. `images/icon10.png` - AI 赋能海外电商
11. `images/icon11.png` - 获客指导与培训

## 业务详情页面

- `images/app-mockup.jpg` - NFC 系统演示
- `images/takeout-dashboard.png` - 团购外卖代运营平台
- `images/video-funnel.png` - 视频号+爆店码营销漏斗
- `images/media-platforms.jpg` - 全媒体营销矩阵
- `images/ai-live-full.jpg` - AI 赋能直播系统
- `images/digital-human.jpg` - AI 数字人形象
- `images/angry-customer.png` - 传统客服示意图(愤怒的客户)
- `images/ai-customer-service.png` - AI 客服形象
- `images/ai-model.png` - 企业 AI 训练模型示意图
- `images/ai-device1.jpg` - AI 智慧一体机应用 1
- `images/ai-device2.jpg` - AI 智慧一体机应用 2
- `images/ai-gov.jpg` - 政务场景应用
- `images/ai-edu.jpg` - 教育场景应用
- `images/ai-medical.jpg` - 医疗场景应用
- `images/ai-retail.jpg` - 零售场景应用
- `images/ai-badge.png` - AI 徽章

## 页脚

- `images/qr-code.jpg` - 微信二维码

## 其他资源

- Bootstrap Icons (通过 CDN 加载)
