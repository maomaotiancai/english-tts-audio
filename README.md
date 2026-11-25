# english-tts-audio

儿童英语单词卡「我的家乐园」预生成英文发音音频素材。

- **语音性质**：AI 合成语音，非真人录音；仅供个人家庭学习使用。
- **音色**：
  - `woman` — 英式女声，en-GB-SoniaNeural（默认）
  - `man` — 英式男声，en-GB-RyanNeural
- **规格**：MP3，32kbps，单声道，24kHz；文件名 = 规范化文本 MD5 前 10 位。
- **目录**：`audio/<voice>/<hash>.mp3`；`index.json` 为文本清单（hash → 原文、分类、各音色相对路径）。
- **慢速**：不在仓库内单独出慢速音频，由播放端降速实现。
