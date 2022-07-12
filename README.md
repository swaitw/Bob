<p align="center">
  <img src="https://cdn.ripperhe.com/oss/master/2019/1222/bob-logo.png" width=240 />
</p>
<p align="center">
	<a href="https://bobtranslate.com"><img src="https://img.shields.io/badge/%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-bobtranslate.com-brightgreen?logo=Safari" alt="Website" /></a>
  <a href="https://bobtranslate.com/general/contact.html"><img src="https://img.shields.io/badge/QQ%20%E7%BE%A4-459542798-blue?logo=Tencent%20QQ" alt="QQ 群" /></a>
</p>

# Bob

Bob 是一款 macOS 平台 **翻译** 和 **OCR** 软件。

> **Bob 商店版目前首发限时 6 折优惠，2022 年 7 月 18 日恢复原价，详情请查看 [这篇文章](https://bobtranslate.com/blog/2022-07-03-v1-coming.html)。**

翻译功能：

- [x] 划词翻译
- [x] 截图翻译
- [x] 输入翻译
- [x] 翻译多开
- [x] 自定义插件
- [x] 自动识别语种
- [x] 驼峰拆分、蛇形拆分
- [x] AppleScript 调用
- [x] PopClip 调用

OCR 功能：

- [x] 截图 OCR
- [x] 静默截图 OCR
- [x] 访达选图 OCR
- [x] 离线识别
- [x] 连续识别
- [x] 二维码识别
- [x] 自动复制
- [x] 智能分段

## 安装

系统要求 **macOS 10.13** 以上。

Bob 1.0.0 版本开始，正式发布到 Mac App Store，从 App Store 安装即可。

[![Download on the Mac App Store](https://cdn.ripperhe.com/oss/master/2022/0626/Download_on_the_Mac_App_Store_Badge_US-UK_RGB_blk_092917.svg)](https://apps.apple.com/cn/app/id1630034110#?platform=mac)

如果您是 Bob 1.0.0 以下版本的老用户（不包括 1.0.0），请查看 [这篇文档](https://bobtranslate.com/blog/2022-07-03-v1-coming.html)。

## 使用方法

详细使用方法请直接查看文档 [👉 点此跳转文档](https://bobtranslate.com)

Bob 是一个菜单栏软件，启动之后，菜单栏会出现一个图标，点击菜单选项即可触发相应的功能，如下所示：

<img src="https://cdn.ripperhe.com/oss/master/2022/0627/status_item.jpg" alt="statesitem.jpg" width=548>

### 翻译功能

| 方式 | 描述 | 预览 |
| :---: | :---: | :---: |
| 划词翻译 | 选中需要翻译的文本之后，按下划词翻译快捷键即可（默认 `⌥ + D`） | ![划词翻译-句子](https://cdn.ripperhe.com/oss/master/2022/0508/translate_selection.gif) |
| 截图翻译 | 按下截图翻译快捷键（默认 `⌥ + S`），截取需要翻译的区域 | ![截图翻译-句子](https://cdn.ripperhe.com/oss/master/2022/0508/translate_snip.gif) |
| 输入翻译| 按下输入翻译快捷键（默认 `⌥ + A`），输入需要翻译的文本，`Enter` 键翻译 | ![输入翻译-单词](https://cdn.ripperhe.com/oss/master/2022/0508/translate_input.gif) |
| PopClip 调用 | 选中需要翻译的文本之后，点击 [PopClip](https://pilotmoon.com/popclip) 插件图标即可，详情见 [PopClip 调用](https://bobtranslate.com/guide/integration/popclip.html) | ![插件翻译-句子](https://cdn.ripperhe.com/oss/master/2022/0508/translate_popclip.gif) |

### OCR 功能

**截图识别**

* 按下「截图 OCR」快捷键（默认 `⇧ + ⌥ + S`）或者点击菜单栏 Bob 图标菜单中的「截图 OCR」
* 选中屏幕上的对应的位置
* 松手即可开始识别

<img src="https://cdn.ripperhe.com/oss/master/2022/0507/snip_ocr.gif" alt="截图 OCR" width=660 />

**静默截图 OCR**

* 按下「静默截图 OCR」快捷键（没有设置默认快捷键，可去「 Bob 偏好设置-OCR-OCR 设置」添加）或者点击菜单栏 Bob 图标菜单中的「静默截图 OCR」
* 选中屏幕上的对应的位置
* 松手即可开始识别

「静默截图 OCR」不会自动显示 OCR 窗口，识别完成后直接将文本拷贝到剪切板。

**访达选图 OCR**

按下「访达选图 OCR」快捷键（没有设置默认快捷键，可去「 Bob 偏好设置-OCR-OCR 设置」添加）或者点击菜单栏 Bob 图标菜单中的「访达选图 OCR」。

在弹出的访达窗口中选中对应的图片文件（可以一次性选中多张），点击右下角「开始识别」即可。

<img src="https://cdn.ripperhe.com/oss/master/2022/0507/file_ocr.jpg" alt="访达选图 OCR" width=600 />

## 感谢

* 感谢 [@isee15](https://github.com/isee15/Capture-Screen-For-Multi-Screens-On-Mac) 提供最初版本截图功能的思路
* 感谢 [@可口可乐](https://github.com/wakewon) 长期帮忙解决用户反馈
* 感谢 [@ix4n33](https://github.com/IsaacXen) 不定期提供技术支持
* 感谢朋友们的赞赏 [赞赏列表](https://bobtranslate.com/general/reward.html)
* 感谢作者们发文支持 Bob（时间倒序）
    * @奇客派：[macOS 翻译工具 Bob 大更新：支持更多翻译服务，增强 OCR 功能](https://sspai.com/post/62721)
    * @鹿額：[截图/划词/输入都能查，快捷高效的 macOS 翻译工具: Bob](https://sspai.com/post/58249)
    * @Newlearnerの自留地：[Bob：一款 macOS 全局翻译软件，支持划词翻译和截图翻译](https://t.me/NewlearnerChannel/3329)

## 优秀软件推荐

* [uPic: 一个强大的图床工具](https://github.com/gee1k/uPic)
* [MWeb Pro: 专业的 Markdown 写作、记笔记、静态博客生成软件](https://zh.mweb.im/)

## 最后

Bob 不是开源软件，目前本仓库主要用于提供反馈渠道。

[👉 点此查看联系方式](https://bobtranslate.com/general/contact.html)
