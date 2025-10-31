# 图片文件夹使用说明

## 📁 图片列表

请将以下图片放入此文件夹中，页面将自动加载显示。如果图片不存在，对应区域会自动隐藏。

### 1️⃣ 个人照片
- **profile.jpg** - 个人头像照片（建议尺寸：800x800px，正方形）

### 2️⃣ 证书照片
- **certificate-degree.jpg** - 北京工商大学本科学历证书
- **certificate-topsec.jpg** - 天融信认证售前中级工程师证书
- **certificate-baidu.jpg** - 百度熊掌号100小时通关训练营证书
- **certificate-ai.jpg** - 人工智能开发工程师证书

### 3️⃣ 项目照片

#### 2025年项目
- **project-jiamada-1.jpg** - 嘉吗达新材料公司项目照片1
- **project-jiamada-2.jpg** - 嘉吗达新材料公司项目照片2

#### 2024年项目
- **project-jiaomei-ai-1.jpg** - 焦煤集团AI数据库建设照片1
- **project-jiaomei-ai-2.jpg** - 焦煤集团AI数据库建设照片2
- **project-jiaomei-ai-3.jpg** - 焦煤集团AI数据库建设照片3
- **project-shenhua-1.jpg** - 神华重机厂信息化建设照片1
- **project-shenhua-2.jpg** - 神华重机厂信息化建设照片2
- **project-dangxiao-1.jpg** - 焦作党校综合楼项目照片1
- **project-dangxiao-2.jpg** - 焦作党校综合楼项目照片2
- **project-dangxiao-3.jpg** - 焦作党校综合楼项目照片3

#### 2023年项目
- **project-jiedusuo-1.jpg** - 焦作戒毒所智慧改造照片1
- **project-jiedusuo-2.jpg** - 焦作戒毒所智慧改造照片2
- **project-jiedusuo-3.jpg** - 焦作戒毒所智慧改造照片3
- **project-jiedusuo-4.jpg** - 焦作戒毒所智慧改造照片4

#### 2021年项目
- **project-jianchayuan-1.jpg** - 马村检察院联网项目照片1
- **project-jianchayuan-2.jpg** - 马村检察院联网项目照片2
- **project-xiaoxue-1.jpg** - 实验小学云桌面项目照片1
- **project-xiaoxue-2.jpg** - 实验小学云桌面项目照片2

#### 2020年项目
- **project-xiwu-1.jpg** - 修武公安局视频监控照片1
- **project-xiwu-2.jpg** - 修武公安局视频监控照片2
- **project-shuiku-1.jpg** - 群英水库渠道智慧化照片1
- **project-shuiku-2.jpg** - 群英水库渠道智慧化照片2
- **project-shuiku-3.jpg** - 群英水库渠道智慧化照片3
- **project-shuiku-4.jpg** - 群英水库渠道智慧化照片4
- **project-jishixueyuan-1.jpg** - 焦作技师学院项目照片1
- **project-jishixueyuan-2.jpg** - 焦作技师学院项目照片2
- **project-jishixueyuan-3.jpg** - 焦作技师学院项目照片3
- **project-linye-1.jpg** - 焦作林业局5G检测照片1
- **project-linye-2.jpg** - 焦作林业局5G检测照片2

#### 2015年项目
- **project-caijing-1.jpg** - 郑州财经学院云桌面照片1
- **project-caijing-2.jpg** - 郑州财经学院云桌面照片2

#### 2012年项目
- **project-91hospital-1.jpg** - 91医院弱电工程照片1
- **project-91hospital-2.jpg** - 91医院弱电工程照片2

## 📝 图片要求

### 格式要求
- **格式**：jpg, jpeg, png, webp 均可
- **命名**：严格按照上述文件名（区分大小写）
- **大小**：建议单张图片不超过2MB，以保证页面加载速度

### 尺寸建议
- **个人照片**：800x800px（正方形，将自动裁剪为圆形）
- **证书照片**：1000x700px（横向，4:3比例）
- **项目照片**：1200x800px（横向，3:2比例）

### 质量建议
- 使用清晰、高质量的照片
- 避免模糊、曝光过度或不足的照片
- 项目照片建议展示实际工作场景、设备安装、系统界面等

## 🔧 技术说明

页面使用了 `onerror` 属性来处理图片缺失的情况：
- 如果图片文件不存在，该图片区域会自动隐藏
- 不会显示破损的图片图标
- 不影响页面其他部分的正常显示

## 📂 文件夹结构示例

```
/workspace/
  ├── index.html
  └── images/
      ├── README.md (本文件)
      ├── profile.jpg
      ├── certificate-degree.jpg
      ├── certificate-topsec.jpg
      ├── certificate-baidu.jpg
      ├── certificate-ai.jpg
      ├── project-jiamada-1.jpg
      ├── project-jiamada-2.jpg
      ├── project-jiaomei-ai-1.jpg
      └── ... (其他项目照片)
```

## ✅ 使用步骤

1. 准备好所需的照片文件
2. 按照上述命名规范重命名文件
3. 将文件放入 `/workspace/images/` 文件夹
4. 在浏览器中打开或刷新 `index.html` 页面
5. 照片将自动显示在相应位置

## 💡 提示

- 不是所有照片都必须提供，页面会优雅地处理缺失的图片
- 建议优先准备：个人照片、证书照片和重点项目照片
- 可以先上传部分照片测试效果，再逐步补充完整
