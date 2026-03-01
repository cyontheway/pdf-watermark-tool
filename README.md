# PDF Watermark Tool (离线 PDF 水印工具)

基于浏览器的纯前端 PDF 水印添加工具。无需安装任何软件，无需上传文件到服务器，安全、离线可用。

## 版本说明

| 文件 | 说明 |
|------|------|
| `pdf-watermark.html` | V1 基础版 — 字号、透明度、旋转、颜色 |
| `pdf-watermark-v2.html` | V2 增强版 — 在 V1 基础上新增密度和位置控制 |

两个版本均已修复扫描件 PDF 水印方向错误的问题。

## 特性

- **100% 隐私安全**：所有处理均在浏览器本地内存中完成，文件绝不上传至任何服务器
- **零依赖**：单 HTML 文件，双击即用，无需 Python/Node.js 环境
- **批量处理**：支持拖拽多个 PDF 文件批量添加水印
- **完全离线**：断网也能正常使用
- **实时预览**：竖版/横版 A4 双视图预览
- **中文支持**：Canvas 渲染，系统字体直出

### V1 可调参数

字体大小 / 透明度 / 旋转角度 / 水印颜色（预设 + 自定义）

### V2 新增参数

- **水印密度**（10%~100%）— 控制水印之间的间距
- **X 偏移**（-200~200）— 水印网格整体左右平移
- **Y 偏移**（-200~200）— 水印网格整体上下平移

## 使用方法

1. 下载 `pdf-watermark-v2.html`（推荐）或 `pdf-watermark.html`
2. 使用 Chrome / Edge / Firefox 浏览器打开
3. 拖入 PDF 文件，设置水印参数，点击"开始添加水印"

> 不支持 Internet Explorer 浏览器

## 依赖与致谢

本项目构建于以下开源库之上（已内嵌至单文件中）：

- [pdf-lib](https://github.com/Hopding/pdf-lib) (MIT License) - PDF 文档操作
- [pako](https://github.com/nodeca/pako) (MIT License) - 数据压缩
- [tslib](https://github.com/microsoft/tslib) (0BSD/Apache-2.0) - TypeScript 运行时库

## 免责声明

本项目按"原样"提供，不提供任何形式的明示或暗示担保。作者不对使用本工具导致的任何数据丢失、文件损坏或其他后果承担责任。建议在使用前备份重要文件。

## License

[MIT License](./LICENSE)
