# Video Translation Agent

<a target="_blank" href="https://colab.research.google.com/github/imkasen/video-translation-agent/blob/main/video_translator.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

使用 LangChain 构建的 LLM Agent，利用 Faster Whisper 和 Google Gemini API 生成并翻译视频字幕。

在 Google Colab 环境下：

1. 使用 Faster Whisper 对视频 / 音频进行语音识别，并生成字幕文件
2. 利用 Google Gemini 对源字幕进行翻译，并生成双语字幕文件

你需要准备一个 Google Gemini API。
