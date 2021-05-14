# 1 背景
基于VUE/Element/WebAssemby/C++/FFMPEG实现的纯前端音频转码器，目前支持市面常见的音频如.mp3、.wav、.flac、.aac...等转为.mp3/.wav。
# 2 代码
github地址: [https://github.com/alyen028/audioTranscoder](https://github.com/alyen028/audioTranscoder).
# 3 依赖
## 3.1 WASM
WASM的介绍在[这里](https://webassembly.org/)，可以在浏览器里执行原生代码(例如C、C++)，要开发可以在浏览器运行的原生代码，需要安装他的[工具链](https://emscripten.org/docs/getting_started/downloads.html)，我使用的版本是(1.38.38)。编译环境有Ubuntu、MacOS等，[这里](https://emscripten.org/docs/getting_started/downloads.html#platform-notes-installation-instructions-sdk)有介绍。
## 3.2 FFmpeg
主要使用FFmpeg来做解封装(demux)和解码(decoder)，所用版本4.1.2，其余涉及相关aac、mp3...等编码库均从相关官方下载并对应边缘emscripten版本。

## 3.3 VUE 3.X
## 3.4 Elelment-Plus V1.X 
# 4 界面
![image](https://github.com/alyen028/audioTranscoder/blob/main/demo1.jpg)
![image](https://github.com/alyen028/audioTranscoder/blob/main/demo2.jpg)
![image](https://github.com/alyen028/audioTranscoder/blob/main/demo3.jpg)
