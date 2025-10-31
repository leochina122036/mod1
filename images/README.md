# 图片文件夹使用说明

## 📁 需要准备的图片文件（WebP格式）

请将以下图片文件放入 `/workspace/images/` 文件夹中。

### 个人照片
- **profile.webp** - 个人头像照片（建议尺寸：800x800px）

### 项目照片（按顺序命名）
- **ai-app1.webp** - 嘉吗达AI大模型项目
- **project1.webp** - 焦煤集团AI数据库建设
- **project2.webp** - 神华重机厂办公楼信息化
- **project3.webp** - 焦作党校综合楼信息化
- **project4.webp** - 焦作戒毒所智慧改造
- **project5.webp** - 马村检察院智慧检察
- **project6.webp** - 实验小学云桌面系统
- **project7.webp** - 焦作林业局5G检测
- **project8.webp** - 群英水库渠道智慧化

### 证书照片
- **cert1.webp** - 北京工商大学本科学历证书
- **cert2.webp** - 天融信认证售前中级工程师证书
- **cert3.webp** - 百度熊掌号100小时通关训练营证书
- **cert4.webp** - 人工智能开发工程师证书

## 📝 图片命名规则

所有图片文件名必须**完全匹配**上述列表（区分大小写），文件格式为 `.webp`。

## 🎨 图片规格建议

### 尺寸要求
- **个人照片**：800x800px（正方形）
- **项目照片**：1200x800px（16:9或3:2比例）
- **证书照片**：1200x900px（4:3比例）

### WebP质量
- 建议质量：85-90
- 单张文件大小：< 500KB

## 🔧 如何转换为WebP格式

### 在线工具
1. [CloudConvert](https://cloudconvert.com/jpg-to-webp) - 支持批量转换
2. [Convertio](https://convertio.co/zh/jpg-webp/) - 简单易用
3. [Squoosh](https://squoosh.app/) - Google出品，质量控制精确

### 命令行工具（推荐批量转换）
```bash
# 安装cwebp
# Ubuntu/Debian: sudo apt install webp
# macOS: brew install webp

# 单个文件转换
cwebp input.jpg -q 85 -o output.webp

# 批量转换当前目录所有jpg
for file in *.jpg; do 
    cwebp "$file" -q 85 -o "${file%.jpg}.webp"
done
```

## 📂 完整文件结构

```
/workspace/
  ├── index.html
  └── images/
      ├── README.md (本文件)
      ├── profile.webp
      ├── ai-app1.webp
      ├── project1.webp
      ├── project2.webp
      ├── project3.webp
      ├── project4.webp
      ├── project5.webp
      ├── project6.webp
      ├── project7.webp
      ├── project8.webp
      ├── cert1.webp
      ├── cert2.webp
      ├── cert3.webp
      └── cert4.webp
```

## ✅ 使用步骤

1. 准备好原始图片文件（JPG/PNG格式）
2. 使用上述工具转换为WebP格式
3. 按照文件名列表重命名文件
4. 将所有文件放入 `/workspace/images/` 目录
5. 在浏览器中打开 `index.html` 查看效果

## 💡 提示

- ✅ 图片缺失不会影响页面显示，系统会自动隐藏或显示占位符
- ✅ 可以先上传部分图片测试效果
- ✅ 建议优先上传：个人照片、AI项目照片、证书照片
- ✅ 文件名必须严格匹配，注意大小写

## 🎯 优先级

### 高优先级（必备）
1. profile.webp - 个人头像
2. ai-app1.webp - AI项目展示
3. cert1.webp 到 cert4.webp - 证书展示

### 中优先级（推荐）
- project1.webp 到 project4.webp - 近期重点项目

### 低优先级（可选）
- project5.webp 到 project8.webp - 其他项目
