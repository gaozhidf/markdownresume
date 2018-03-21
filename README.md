[![Build Status](https://travis-ci.org/gaozhidf/markdownresume.svg?branch=master)](https://travis-ci.org/gaozhidf/markdownresume)

本简历 参考 自 xuxiaodong 的 [Resume][r]。

## 准备环境

0. 测试环境:
    `Deepin 15.5 + Chrome 63.0`

1. 安装 Node.js 模块：
    `npm install`
2. 运行(可以实时修改):
    `npm run dev`

## 生成简历

1. 修改resume.md,和css/resume.css
2. 对resume.css,里面做了一点简单的屏幕适配
3. 打印简历: 在chrome中,右键打印,便可打印简历(打印的样式可以在resume.css中的`@media print`中修改)

[r]: https://github.com/xuxiaodong/resume
