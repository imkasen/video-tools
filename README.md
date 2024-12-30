# Video Translation Agent Using Google Gemini

<a target="_blank" href="https://colab.research.google.com/github/imkasen/video-translation-agent/blob/main/video_translator.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Generate and translate video subtitles using LLM Agent built by LangChain with [Faster Whisper](https://github.com/SYSTRAN/faster-whisper) and [Google Gemini API](https://aistudio.google.com/apikey).

## Steps

In Google Colab:

1. Use FFmpeg to get the audio from your uploaded video file.
2. Use Faster Whisper to perform speech recognition and generate the subtitle file.
3. Use Google Gemini to translate the source subtitle and generate the bilingual subtitle file.
