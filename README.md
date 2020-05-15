# esp32-wrover-micropython
> 适用于ESP32-WROVER-B（IB）模组的MicroPython固件
## 简介
本固件基于MicroPython 4月24日快照版本构建，默认构建目标为ESP32-WROVER系列模组，并提供`Real Efuse`和`Virtual Efuse`两种版本供开发人员选用。

## 特点
* 上电默认频率即为240MHz，提高代码运行效率
* 可选的电子保险丝（`Efuse`）保护功能，防止Efuse被恶意烧写导致芯片运行异常
* 开启`SPIRAM`支持，可额外增加约`4MB`的内存空间
* 默认有`2MB`的文件存储空间

## 使用方法
在本仓库内下载固件并烧录即可，烧录过程参考官方MicroPython烧录教程。

## 开放源代码许可
本仓库存储的MicroPython固件修改自官方MicroPython固件。
### Micropython
MIT License
```
The MIT License (MIT)

Copyright (c) 2013-2016 Damien P. George

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
