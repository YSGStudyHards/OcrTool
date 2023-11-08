# OcrTool
一个基于百度飞桨封装的.NET版本OCR工具类库（[PaddleOCRSharp](https://gitee.com/raoyutian/paddle-ocrsharp)）开发的WinForm OCR图文识别小工具。

# PaddleOCRSharp介绍
PaddleOCRSharp 是一个基于百度飞桨PaddleOCR的.NET版本OCR工具类库。项目核心组件PaddleOCR.dll,由C++编写，根据百度飞桨PaddleOCR的C++代码修改并优化而成。目前已经支持C++、.NET、Python、Golang、Rust等开发语言的直接API接口调用。项目包含文本识别、文本检测、表格识别功能。本项目针对小图识别不准的情况下做了优化，比飞桨原代码识别准确率有所提高。包含总模型仅8.6M的超轻量级中文OCR，单模型支持中英文数字组合识别、竖排文本识别、长文本识别。同时支持中英文、纯英文以及多种语言文本检测识别。
