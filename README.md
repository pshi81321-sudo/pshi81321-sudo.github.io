# pshi81321-sudo.github.io

裴士忠（Shizhong Pei）的个人主页，由 GitHub Pages 免费托管。

- 域名：https://pshi81321-sudo.github.io/
- 仓库：https://github.com/pshi81321-sudo/pshi81321-sudo.github.io

## 技术栈

纯静态 HTML + CSS（无构建步骤、无依赖），学术简洁风。

## 本地预览

直接用浏览器打开 `index.html` 即可，或起一个静态服务器：

```bash
# Python
python -m http.server 8080

# 或在 Node 环境
npx serve .
```

## 结构

```
index.html   页面主体（简介 / 教育 / 荣誉 / 联系）
style.css    样式（学术简洁风，深藏青主色）
README.md    本文件
```

## 维护说明

- 荣誉信息来源为公开报道（南京理工大学喜报，见页面荣誉节脚注），如需补充
  专业、年级、获奖年份等细节，直接编辑 `index.html` 对应区块。
- 联系方式中的邮箱为占位符，请替换为真实邮箱。
- 页面为响应式设计，移动端自动适配。