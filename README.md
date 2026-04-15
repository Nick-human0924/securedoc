# SecureDoc

🔒 **本地隐私文档处理工具**

PDF 涂黑、拆分、合并、压缩 —— 全部在浏览器本地完成，文件不上传服务器。

## 特性

- **零云端** - 文件从不上传任何服务器
- **零日志** - 不记录任何操作或文件信息  
- **零残留** - 关闭页面后自动清空所有数据

## 功能

- 🖍️ **PDF 涂黑** - 永久抹除敏感信息（基于 pdf.js 预览 + pdf-lib 处理）
- ✂️ **PDF 拆分** - 按页码范围或逐页拆分
- ⧉ **PDF 合并** - 多文件合并，拖拽调整顺序
- ⌇ **PDF 压缩** - 减小文件体积

## 技术栈

- 原生 HTML/CSS/JavaScript
- [pdf-lib.js](https://pdf-lib.js.org/) - PDF 处理
- [pdf.js](https://mozilla.github.io/pdf.js/) - PDF 预览
- 部署：GitHub Pages

## 在线使用

🔗 https://nick-human0924.github.io/securedoc/

## 本地运行

```bash
git clone https://github.com/Nick-human0924/securedoc.git
cd securedoc
# 用任意 HTTP 服务器打开
python3 -m http.server 8080
```

## 隐私说明

所有处理完全在浏览器本地完成。文件不会被上传到任何服务器，刷新页面后所有临时数据自动清除。

详见 [privacy.html](privacy.html)

## 开源

MIT License - 详见 LICENSE 文件
