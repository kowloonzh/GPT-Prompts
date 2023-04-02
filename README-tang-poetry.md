##  Tang poetry Prompt Generator

Tang poetry Prompt Generator是一个利用唐诗三百首生成 AI 作图提示词的提示词生成器。。

### 如何使用

从[此链接](https://github.com/kowloonzh/GPT-Prompts/blob/main/tang-poetry-prompt-generator.txt) 拷贝到 chatGPT,建议打开一个 NEW CHAT,示例中我使用的是 ChatHUB

然后可以随时向 chatGPT 发送以下命令之一，TA将以所需输出进行回应：

#### /rs

-   从唐诗三百首中随机选出的描写人物或风景的句子，每首两句，并将其翻译成英语。

![rs](https://kowloonzh.github.io/imgse/tmp/chatgpt-rs.jpg)

#### /img "[scene]"
-   如果是中文唐诗，先翻译成英文。
-   返回一个带有关键元素的提示，用于拍摄指定场景的照片。
-   每个关键元素之间应用逗号分隔。
-   用 ancient chinese painting 结尾，生成的 prompt 总长度不超过 75 字符。


![img](https://kowloonzh.github.io/imgse/tmp/img_jingyesi.jpg)

#### /img [number]

-   此命令充当 /img "[/rs结果编号]"。

![img-num](https://kowloonzh.github.io/imgse/tmp/img_num.jpg)

### 免责声明

Tang poetry Prompt Generator是一个提供基于其AI模型的创意建议和推荐的工具。AI接受的知识截止日期为2021年9月，可能不包括摄影领域的最新进展或趋势。用户在使用生成的提示时，应将其视为灵感来源，并进行自己的研究，运用自己的判断。

在生成图片时，请始终尊重遵守当地法律法规。Tang poetry Prompt Generator的创建者对由该工具生成的任何误用或不当内容概不负责。

### 致谢

Tang poetry Prompt Generator 深度参考了 [midjourney-prompt-generator](https://github.com/jesselau76/GPT-Prompts/blob/main/midjourney-prompt-generator/README-zh.md)
。
