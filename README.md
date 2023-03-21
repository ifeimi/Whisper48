# WhisperX48

English | [简体中文(编写中)](https://github.com/ifeimi/WhisperX48/blob/main/README_CN.md)
　　
## 云端运行 Working on Google Colab

Stable-ts: This project is deployed as a notebook on Google Colab, [click to open](https://colab.research.google.com/github/ifeimi/WhisperX48/blob/main/stable-ts.ipynb).  
\
WhisperX: Not available for now.  
\
　　
## 本地运行 Working locally

Unfortunately at the moment the Jupyter Notebook for WhisperX usage is not working correctly. Therefore I opened this stupid [shell usage script for WhisperX](https://colab.research.google.com/github/ifeimi/WhisperX48/blob/main/WhisperX48_shell.ipynb) only. You may need a little bit relevant knowledge to use it, but I have also provided adequate helping notes which I believe should be sufficient.  
　　
## 示例 Examples

I will update some subtitile examples generated by WhisperX in the near future. This will include subtitles for short videos, long videos, and music-containing videos. However corresponding video or audio file will not be provided due to copyright reasons.  
　　
## 参与 Contribute

Right now I'm adding python usage of some other whisper-based tools, whisperX and stable-whisper for example, in order to generate more accurate timestamps.  
\
Comparison between different models are being made.  
\
I modify this project strongly according to my demands. But feel free to submit issues or directly contact me if you have any suggestions. I also encourage you to contribute to the "original" [N46Whisper](https://github.com/Ayanaminn/N46Whisper) project as well. 
  
## 联系和帮助 Contact and Support

This project is designed to significantly reduce the workload in subtitle editting, especially timestamping. As a bonus, AI tools are now able to help us in translations as well. That means, even if you don't know much about the original language, making translated subtitiles in your own language is actually possible. Nevertheless, although I do consider using fully auto-generated AI-translated subtitles for less important videos (full-length [SHOWROOM](https://www.showroom-live.com/) recordings for example), AI translation is of course far from perfect (even GPT4!) and manual adjust (sometimes a lot) is a must when translation quality is a demand. For my own experiences, different translation tools can be consulted: [ChatGPT](https://openai.com/blog/chatgpt), [DeepL](https://www.deepl.com/translator), [Google Translate](https://translate.google.com/), and a very helpful web dictionary of my favorite - [Jisho.org](https://jisho.org/).  
\
The timestamps generated by [Whisper](https://github.com/openai/whisper) are not perfect either. Long video, conversation, blank, and background noise can cause large inaccuracy in the generated timestamp. This is the problem these developers have been working on in its [recent releases](https://github.com/openai/whisper/blob/main/CHANGELOG.md), and this is the reason why I would try other improved models like [WhisperX](https://github.com/m-bain/whisperX). Once this problem is solved, timestamping would become a fully automatic and labor-free work: fantastic news for all subtitilers! I believe genius developers from OpenAI and other institutes will make progress on this problem shortly.  
\
Contact me anytime by email: yfwu0202 AT gmail.com. I would love to help with any questions and hear any kind suggestions from you.  
\
Please also consult documentations for [Whisper](https://github.com/openai/whisper/blob/main/README.md), [WhisperX](https://github.com/m-bain/whisperX/blob/main/README.md), and [N46Whisper](https://github.com/Ayanaminn/N46Whisper/blob/main/README.md). 
　　
## 致谢和版权 Acknowledgements and Copyright notice  

This project started as a fork from [N46Whisper](https://github.com/Ayanaminn/N46Whisper). Majority of the code was left unchanged and used under [MIT license](https://github.com/ifeimi/WhisperX48/blob/main/LICENSE). Modifications were made to incorporate the usage of more accurate Whisper-based models ([WhisperX](https://github.com/m-bain/whisperX) for example) and to adapt for other personal demands.  
\
This script relies on [WhisperX](https://github.com/m-bain/whisperX), which provides an improvement to [OpenAI's Whisper](https://github.com/openai/whisper) with more accurate and even word-level timestamps. This is achieved by forcing align the inaccurate timestamps generated by whisper with some speech model ([wav2vec2.0](https://huggingface.co/facebook/wav2vec2-large-960h-lv60-self) for example). Another attempt was made on [stable-ts](https://github.com/jianfch/stable-ts), another tool stabilizing timestamps for Whisper which unfortunately is no longer up-to-date after [the very recent releases of Whisper](https://github.com/openai/whisper/blob/main/CHANGELOG.md).  
\
This project is released under the MIT license. See [LICENSE](https://github.com/ifeimi/WhisperX48/blob/main/LICENSE) for further details. \
\
本说明文档的最后更新时间为 2023-03-15。\
This README file was last modified on 2023-03-15. \
\
\
![GitHub](https://img.shields.io/github/license/ifeimi/WhisperX48)
