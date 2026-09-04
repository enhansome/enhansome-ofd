# Awesome OFD with stars

精选的中国开放文档格式(OFD)相关资源列表。

在使用Awesome OFD资源列表之前,请务必阅读我们的[免责声明](DISCLAIMER.md)。

## 目录

* [OFD文档](#OFD文档)
* [OFD特点](#OFD特点)
* [标准规范](#标准规范)
* [库和SDK](#库和SDK)
* [转换工具](#转换工具)
* [阅读器](#阅读器)
* [文章和教程](#文章和教程)

## OFD文档

OFD（Open Fixed-layout Documents的简称，意为开放版式文件）版式文档是版面呈现效果高度精确固定的电子文件，其呈现与设备无关。与pdf文件相仿，具有格式独立、版面固定、固化呈现等特点。OFD也逐渐开始在电子发票、电子公文、电子证照等等的领域中应用。

## OFD特点

OFD标准有一系列技术优势。

1. 体积精简，格式开放，利于理解，长期可读可用
2. 根据我国各领域特色需要进行特性扩展，更深入地贴合了应用需求
3. 标准可支持国产密码算法，是文档安全性的有力保证，也是文件具有法律效力的基本条件
4. 标准是自主可控的，国家再有需要对OFD做上面提到的扩展时，特别是在我国党政军严肃类文档应用领域，可以不受控于外部的厂商，我们有自主的标准话语权

## 标准规范

* [GB/T 33190-2016](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=3AF6682D939116B6F5EED53D01A9DB5D) - 电子文件存储与交换格式版式文档

## 库和SDK

* [ofdrw](https://github.com/ofdrw/ofdrw) ⭐ 1,859 | 🐛 45 | 🌐 Java | 📅 2026-08-04 - OFD Reader & Writer 开源的OFD处理库，支持文档生成、数字签名、文档保护、文档合并、转换、导出等功能(Java)
* [easyofd](https://github.com/renoyuan/easyofd) ⭐ 440 | 🐛 58 | 🌐 Python | 📅 2026-06-11 - Python实现的OFD处理库纯 python的ofd解析与pdf转换(Python)
* [ofd.js](https://github.com/DLTech21/ofd.js) ⭐ 337 | 🐛 25 | 🌐 JavaScript | 📅 2024-08-13 - OFD板式文件html渲染方案及组件(JavaScript)
* [ofdparser](https://github.com/wangyi160/ofdparser) ⭐ 72 | 🐛 5 | 🌐 Java | 📅 2022-02-11 - OFD解析器(Java)
* [XiaoFeng.Ofd](https://github.com/zhuovi/XiaoFeng.Ofd) ⭐ 54 | 🐛 5 | 🌐 C# | 📅 2025-06-03 OFD 读写处理库(.NET)
* [ofd-go](https://github.com/itlabers/ofd-go) ⭐ 33 | 🐛 0 | 🌐 Go | 📅 2024-03-12 - Go语言实现的OFD处理库(GO)
* [ofdparser](https://github.com/gongdaowen/ofdparser) ⭐ 30 | 🐛 4 | 🌐 Java | 📅 2021-08-13 - OFD电子发票验签、发票信息提取、保存为图片(Java)
* [OfdSharp](https://github.com/swpudp/OfdSharp) ⭐ 27 | 🐛 2 | 🌐 C# | 📅 2022-04-26 - C#实现的OFD处理库 ofd文件读写类库(C#)
* [ofd-analyze](https://github.com/cooker/ofd-analyze) ⭐ 25 | 🐛 6 | 🌐 Java | 📅 2022-05-20 - OFD 发票解析(Python)
* [OFDConverter](https://github.com/wukonggo/OFDConverter) ⭐ 11 | 🐛 2 | 🌐 C# | 📅 2024-10-01 A straightforward PDF to OFD 简易的PDF转换为OFD格式文档
* [ofd-pdf](https://gitee.com/gblfy/ofd-pdf) - ofd和pdf 2种类型文件相互转换和ofd文件在线预览(Java)

## 转换工具

### PDF转OFD方案

1. 使用ofdrw库进行转换
2. 利用Spire.Pdf免费版本，拆分3页转换后合并（每次3页）
3. 使用Google的pdfium将PDF转为图片，再将图片转换为OFD

### 相关工具

* [PdfiumViewer](https://github.com/pvginkel/PdfiumViewer) ⚠️ Archived PdfiumViewer
* [Ofd2Pdf](https://github.com/taurusxin/Ofd2Pdf) ⭐ 190 | 🐛 6 | 🌐 C# | 📅 2023-10-13 - OFD转PDF工具
* [ofdbox](https://github.com/QAQtutu/ofdbox) ⭐ 68 | 🐛 2 | 🌐 Java | 📅 2021-03-26 - 推荐开源OFD图片转换解决方案
* [Spire.Pdf](https://github.com/SpirePDF/FreeSpire.PDF) ⭐ 41 | 🐛 13 | 📅 2023-07-13 free spire.pdf
* [ofd2img](https://github.com/geniusnut/ofd2img) ⭐ 32 | 🐛 6 | 🌐 Python | 📅 2025-12-31 - OFD转图片工具(Python OFD发票转为PNG)
* [pdfium](https://pdfium.googlesource.com/pdfium/) google pdfium

## 阅读器

* [ofd.js](https://github.com/DLTech21/ofd.js) ⭐ 337 | 🐛 25 | 🌐 JavaScript | 📅 2024-08-13 - 基于JavaScript的OFD在线阅读器
* **OfdiumEx**：基于cairo库渲染OFDWindows客户端阅读器[roy19831015/OfdiumEx . https://github.com/roy19831015/OfdiumEx](https://github.com/roy19831015/OfdiumEx) ⭐ 58 | 🐛 2 | 🌐 C | 📅 2021-04-14
* [Foxit Reader](https://www.foxitsoftware.cn/pdf-reader/) - 支持OFD格式的福昕阅读器
* [WPS Office](https://www.wps.cn/) - 支持OFD格式的WPS Office
* [数科网维公司 . 数科OFD阅读器 . www.ofd.cn](https://www.ofd.cn/)
* [Foxit . 福昕OFD . www.foxitsoftware.cn/ofd/](https://www.foxitsoftware.cn/ofd/)
* **XilouReader**：基于pdfium的ofd/pdf双引擎版式阅读器
  [chingliu/XilouReader . https://gitee.com/chingliu/XilouReader](https://gitee.com/chingliu/XilouReader)

## 文章和教程

[理解 PDF 中的五种页面边界](https://sspai.com/post/61716)

[PDF转OFD工具类 Java](https://blog.csdn.net/qq_51239427/article/details/141218181)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
