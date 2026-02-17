# GitHub上传指南

## 📤 上传步骤

### 选项1：直接网页上传（推荐）

1. 访问：https://github.com/new
2. 创建名为 `ecommerce-material-generator` 的新仓库
3. 上传所有文件：
   - 电商v2.html（主程序）
   - index.html
   - 电商v1.html
   - 截图说明.md
   - README.md
   - .gitignore

### 选项2：命令行推送

```bash
# 如果仓库已创建，使用以下命令：
git remote add origin https://github.com/caicaikankan/ecommerce-material-generator.git
git branch -M main
git push -u origin main
```

## 🌐 GitHub Pages配置

1. 进入仓库 → Settings → Pages
2. Source选择 "Deploy from a branch"
3. Branch选择 "main" 和 "/(root)"
4. 点击Save
5. 访问：https://caicaikankan.github.io/ecommerce-material-generator/

## 📋 文件说明

- **电商v2.html**: 主程序文件，包含完整的素材生成工具
- **README.md**: 项目说明文档
- **.gitignore**: Git忽略文件配置

## 🎯 访问地址

GitHub Pages发布成功后，可以通过以下地址访问：
`https://caicaikankan.github.io/ecommerce-material-generator/电商v2.html`