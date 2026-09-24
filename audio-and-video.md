# 音视频文件格式规范

### 一、视频

#### （一）分辨率

1920×1080，根据情况可等比缩小。

#### （二）编码与封装

1. H.264 High Profile 编码。
2. MP4 封装。
3. 14Mbps VBR。
4. Level 4.1。

#### （三）帧率

30fps。

#### （四）色彩与动态范围

SDR 采用 BT.709，8-bit，4:2:0，Limited Range。

#### （五）音频

视频音频轨采用 AAC 48kHz。

### 二、音频

#### （一）游戏内使用

1. 在游戏中使用 OGG Vorbis/MP3。
2. OGG Vorbis 优先。
3. 采用 OGG Vorbis 时，使用 q5 或更高。

#### （二）单独音乐文件

1. 使用 FLAC、MP3。
2. FLAC 无损分发。
3. MP3 兼容。
4. MP3 至少使用 192kbps。
