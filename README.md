
# 极速图片压缩器
### 压缩速度极快的图片压缩软件

<hr>

- [下载软件](#下载软件)
- [软件特点](#软件特点)
- [软件截图](#软件截图)
- [版本记录](#版本记录)
- [快捷按键](#快捷按键)
- [使用说明](#使用说明)
- [在线压缩](#在线压缩)
- [问题反馈](#问题反馈)
- [更新日志](#更新日志)
- [支持平台](#支持平台)
- [版权声明](#版权声明)

<hr>

## 下载软件

- [前往下载](https://www.ticompressor.com/online/)

## 软件特点

- 具有超快的压缩速度
- 支持压缩 `GB` 级别的超大体积的图片
- 支持 `7` 种图片格式
- 支持深、浅色主题模式
- 可对原始图片进行预览
- 可通过【鼠标拖拽】【点击选择】【`ctrl + v` 粘贴】 等多种方式添加图片
- 支持添加文件夹，可自动解析文件夹内所有符合要求的图片
- 实时显示压缩进度
- 完全在本地执行压缩，有无网络均可，不上传图片，充分保证隐私安全

## 软件截图

### 浅色模式

![截图](screenshot/1.png)
![截图](screenshot/2.png)

### 深色模式

![截图](screenshot/3.png)
![截图](screenshot/4.png)

<hr>

## 版本记录

- v1.4.0（发布于 2023-09-06）[前往下载](https://www.ticompressor.com/online/)
- v1.3.0（发布于 2023-08-25）
- v1.2.0（发布于 2023-08-19）
- v1.1.0（发布于 2023-08-07）
- v1.0.0（发布于 2023-07-26）

## 快捷按键

- `Ctrl + Shift + O` 添加文件夹
- `Ctrl + V` 添加图片（粘贴已复制的图片）
- `Ctrl + O` 添加图片（通过弹窗选择图片）
- `Ctrl + A` 选中列表内所有图片
- `Delete` 删除图片（前提：列表中已选择图片）

## 使用说明

-  **分辨率** 
    - 尺寸单位是：像素；
    - 此配置项不支持 `SVG` 格式的图片，即：如果原始图片是 `SVG` 格式，则不支持调整压缩后的宽高；
    - 仅支持输入 `1 - 65535` 范围内的正整数，输入不正确的值将会被自动清空；
    - 如果原始格式或转换后的格式是 `HEIF`，则支持的最大有效值为：`16384`，即：对于 `HEIF` 格式，如果设置了大于 `16384` 的值，将可能导致压缩失败；
    - 如果选中了 “保持原始宽高比”，则 “宽度” 和 “高度” 只能同时设置一个，另一个尺寸将根据原始宽高比自动计算出来；
    - 宽高尺寸设置的越大，则压缩时间越长。
-  **转换格式** 
    - 此配置项不支持 `SVG` 格式的图片，即：如果原始图片是 `SVG` 格式，则不支持调整格式，此时即使选中了其它格式，也不会生效；
    - 如果原始图片含有透明通道，此时选择了压缩后转换格式为 `JPG` 或 `TIFF`，则透明通道将失效。
-  **保存路径** 
    - 选中：原始路径
        - 如果前缀和后缀都不设置，压缩后的图片将直接覆盖原始图片。
    - 选中：自定义路径
        - 选择了自定义路径后，在路径显示位置点击鼠标右键可弹出对应的快捷菜单。
-  **表格区域** 
    - 在列表中右键单击任意数据，都可弹出快捷菜单；
    - 双击列表中任意数据的图片路径文本，可预览原始图片。
-  **软件设置** 
    - 对于 `JPG` 格式，可以选择是否开启 “极限压缩” 功能，一旦开启，压缩后的图片体积会更小，但相应的压缩时间也会略有增加；
    - 开启 “消息通知” 后，当所有图片压缩完成时，会弹出系统级的通知（ `Windows` 系统会在桌面右下角弹出通知）。

## 在线压缩

对于 `JPG` 和 `PNG` 格式的图片，还提供了一个可在浏览器端使用的在线压缩，快去体验吧！

- [立即体验](https://www.ticompressor.com/online/)

## 问题反馈

由于图片的繁杂性以及图片原始数据存在太多的不确定性和多样性，因此在压缩过程中可能会出现很多边界问题和意料之外的情况，进而导致压缩失败，希望使用此软件的用户在遇到上述情况时，能积极反馈相关问题，并在条件允许的情况下，提供原始图片便于进行问题排查。此外，在软件的使用过程中如有任何建议也可随时提交 issue：

- [提交 Issue](https://github.com/Dreamer365/topspeed-image-compressor/issues)

## 更新日志

- [查看日志](https://github.com/Dreamer365/topspeed-image-compressor/blob/main/CHANGELOG.md)

## 支持平台

软件支持 `Windows 10` 和 `Windows 11` 操作系统。

## 版权声明

软件完全免费使用，但不开源，版权仅归作者所有，目前暂无任何授权，不公开软件源码，不允许任何篡改和售卖，不允许用于任何商业用途和非法用途！


