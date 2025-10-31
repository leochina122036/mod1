# 图片文件夹使用说明

## 📁 图片列表（WebP格式）

请将以下图片放入此文件夹中，页面将自动加载显示。所有图片请使用 **WebP格式**（.webp后缀）。

### 1️⃣ 个人照片
- **profile.webp** - 个人头像照片（建议尺寸：800x800px，正方形）

### 2️⃣ 证书照片
- **certificate-degree.webp** - 北京工商大学本科学历证书
- **certificate-topsec.webp** - 天融信认证售前中级工程师证书
- **certificate-baidu.webp** - 百度熊掌号100小时通关训练营证书
- **certificate-ai.webp** - 人工智能开发工程师证书

### 3️⃣ 项目照片

#### 2025年项目
- **project-jiamada-1.webp** - 嘉吗达新材料公司项目照片1
- **project-jiamada-2.webp** - 嘉吗达新材料公司项目照片2

#### 2024年项目
- **project-jiaomei-ai-1.webp** - 焦煤集团AI数据库建设照片1
- **project-jiaomei-ai-2.webp** - 焦煤集团AI数据库建设照片2
- **project-jiaomei-ai-3.webp** - 焦煤集团AI数据库建设照片3
- **project-shenhua-1.webp** - 神华重机厂信息化建设照片1
- **project-shenhua-2.webp** - 神华重机厂信息化建设照片2
- **project-dangxiao-1.webp** - 焦作党校综合楼项目照片1
- **project-dangxiao-2.webp** - 焦作党校综合楼项目照片2
- **project-dangxiao-3.webp** - 焦作党校综合楼项目照片3

#### 2023年项目
- **project-jiedusuo-1.webp** - 焦作戒毒所智慧改造照片1
- **project-jiedusuo-2.webp** - 焦作戒毒所智慧改造照片2
- **project-jiedusuo-3.webp** - 焦作戒毒所智慧改造照片3
- **project-jiedusuo-4.webp** - 焦作戒毒所智慧改造照片4

#### 2021年项目
- **project-jianchayuan-1.webp** - 马村检察院联网项目照片1
- **project-jianchayuan-2.webp** - 马村检察院联网项目照片2
- **project-xiaoxue-1.webp** - 实验小学云桌面项目照片1
- **project-xiaoxue-2.webp** - 实验小学云桌面项目照片2

#### 2020年项目
- **project-xiwu-1.webp** - 修武公安局视频监控照片1
- **project-xiwu-2.webp** - 修武公安局视频监控照片2
- **project-shuiku-1.webp** - 群英水库渠道智慧化照片1
- **project-shuiku-2.webp** - 群英水库渠道智慧化照片2
- **project-shuiku-3.webp** - 群英水库渠道智慧化照片3
- **project-shuiku-4.webp** - 群英水库渠道智慧化照片4
- **project-jishixueyuan-1.webp** - 焦作技师学院项目照片1
- **project-jishixueyuan-2.webp** - 焦作技师学院项目照片2
- **project-jishixueyuan-3.webp** - 焦作技师学院项目照片3
- **project-linye-1.webp** - 焦作林业局5G检测照片1
- **project-linye-2.webp** - 焦作林业局5G检测照片2

#### 其他年份项目
- **project-caijing-1.webp** - 郑州财经学院云桌面照片1
- **project-caijing-2.webp** - 郑州财经学院云桌面照片2
- **project-91hospital-1.webp** - 91医院弱电工程照片1
- **project-91hospital-2.webp** - 91医院弱电工程照片2

## 📝 WebP格式说明

### 为什么使用WebP格式？
- ✅ **更小的文件体积**：相比JPEG/PNG，WebP可减少25-35%的文件大小
- ✅ **更快的加载速度**：减少带宽占用，提升页面加载性能
- ✅ **更好的质量**：在相同文件大小下提供更好的图像质量
- ✅ **现代浏览器支持**：Chrome、Firefox、Safari、Edge均已支持

### 如何转换为WebP格式？

#### 方法1：在线转换工具
- [CloudConvert](https://cloudconvert.com/jpg-to-webp)
- [Convertio](https://convertio.co/zh/jpg-webp/)
- [TinyPNG](https://tinypng.com/) - 支持WebP输出

#### 方法2：使用图像处理软件
- **Photoshop**: 安装WebP插件后另存为WebP格式
- **GIMP**: 安装WebP插件后可导出WebP
- **XnConvert**: 免费批量转换工具

#### 方法3：命令行工具（推荐批量转换）
```bash
# 使用cwebp命令行工具
cwebp input.jpg -q 85 -o output.webp

# 批量转换（Linux/Mac）
for file in *.jpg; do cwebp "$file" -q 85 -o "${file%.jpg}.webp"; done
```

## 📏 图片规格建议

### 尺寸要求
- **个人照片**：800x800px（正方形）
- **证书照片**：1200x900px（4:3比例）
- **项目照片**：1200x800px（3:2比例）

### 质量设置
- **WebP质量**：建议85-90（平衡质量与文件大小）
- **最大文件大小**：单张不超过500KB
- **分辨率**：72-96 DPI（网页标准）

## 🎯 优先级建议

### 高优先级（必备）
1. ✨ **profile.webp** - 个人头像（侧边栏和首页展示）
2. 🏆 **4张证书照片** - 展示专业资质
3. 🚀 **2024-2025年AI项目照片** - 展示最新成果

### 中优先级（推荐）
- 2023年的重点项目照片
- 2021年的代表性项目照片

### 低优先级（可选）
- 早期项目照片
- 补充说明性照片

## 📂 文件夹结构示例

```
/workspace/
  ├── index.html
  └── images/
      ├── README.md (本文件)
      ├── profile.webp
      ├── certificate-degree.webp
      ├── certificate-topsec.webp
      ├── certificate-baidu.webp
      ├── certificate-ai.webp
      ├── project-jiamada-1.webp
      ├── project-jiamada-2.webp
      ├── project-jiaomei-ai-1.webp
      └── ... (其他项目照片)
```

## ✅ 使用步骤

1. **准备照片**：收集所需的项目照片和证书照片
2. **格式转换**：将图片转换为WebP格式
3. **重命名文件**：按照上述命名规范重命名
4. **调整尺寸**：确保图片尺寸符合建议规格
5. **放入文件夹**：将文件放入 `/workspace/images/` 目录
6. **查看效果**：在浏览器中打开 `index.html` 查看

## 🔧 技术说明

### 智能降级处理
页面已配置智能图片加载机制：
- 如果WebP图片不存在，会显示带项目名称的占位图
- 不会出现破损图标
- 不影响页面其他功能正常使用

### 图片加载优化
- 使用了懒加载技术
- 渐进式加载效果
- 响应式图片适配

## 💡 小提示

1. **批量处理**：如果有多张照片需要转换，推荐使用批量转换工具
2. **保持原图**：转换前建议保留原始JPG/PNG文件作为备份
3. **测试查看**：上传部分图片后先测试效果，确认无误后再批量处理
4. **移动优化**：WebP格式特别适合移动端访问，能显著提升加载速度

## 📞 需要帮助？

如果在图片准备过程中遇到问题，可以：
- 先上传少量图片测试效果
- 确保文件名完全匹配（区分大小写）
- 检查图片是否为WebP格式
- 确认图片文件大小合理（建议<500KB）
