# 🤖️ ChatGPT Siri

# 👉 [简体中文文档](README-zh_CN.md)

#-默认使用官方api，如果需要魔法api看q群公告：125800040
自备梯子无需进群
-安卓可以使用网页版：https://chat.aiprm.top
-白嫖密码也在公告中，也可以使用自己的key直接使用。

Start the "Shortcut" through Siri to connect to the ChatGPT API, turning Siri into an AI chat assistant. You can speak your question directly to Siri, and Siri will answer you. Now our Siri has finally become intelligent and can talk to us fluently! And all this can be done with just a Shortcut and an API key.

# Preparation

- Ensure that the network can access the domain name https://api.openai.com.
- Ensure that there is enough balance in the API account: https://platform.openai.com/account/usage.
- Use Siri to start the shortcut: open Settings-> Siri Answer-> Automatic. Check "Always show what you say to Siri" to see if recognition is accurate. Ensure that Siri's language setting matches the language you are using.
- For versions 1.2 and above, you need to turn on the "Settings" - Apple ID - iCloud - iCloud Drive function to use the save to TXT file function.

## Other related issues

- How to use the API key safely: https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety.
- API keys: https://platform.openai.com/account/api-keys.
- API usage: https://platform.openai.com/account/usage.
- API prices: https://openai.com/pricing.
- ChatGPT API FAQ: https://help.openai.com/en/articles/7039783-chatgpt-api-faq.

# Shortcut Download

Click the link below to download shortcuts, support iPhone、iPad、Mac、HomePod、CarPlay.


### ChatGPT Siri 1.2.5

The function is the same as 1.2.4, with the following modifications:

1. Added error message for not finding choices.
2. Removed colon from chat log file name to avoid potential directory issues.

- [简体中文版](https://www.icloud.com/shortcuts/20221b88cbda4496a7a6840858c9af1f)
- [English Version](https://www.icloud.com/shortcuts/e49118e4243e49cbbd29750b1b741a25)

> Currently, GPT-4 requires joining a waitlist. Once you join the waitlist, you will receive a confirmation email. Then, you need to wait for the invitation to use the GPT-4 API, and after you have qualified, you can see the GPT-4 model option for testing in the playground backend. If you do not have GPT-4 qualifications, please choose to use the GPT-3.5-Turbo model. 

- gpt-4 api waitlist: https://openai.com/waitlist/gpt-4-api
- playground：https://platform.openai.com/playground?mode=chat

<div align="center">
<img width="500" src="img/playground-gpt-4.jpg" />
</div>

# API key acquisition

To use the "shortcut" to call the ChatGPT API, an OpenAI API key is required. You can go to the OpenAI official website to get it for free, the steps are as follows:

1. Go to https://platform.openai.com to register an account and log in.
2. Click on the avatar in the upper right corner and select "View API keys".
3. Click the "Create new secret key" button on the right side of the page to generate an API key.
4. Copy the API key for backup. Note that the API key only appears once. If you forgot it, regenerate a new one.


> Note: There is a fee to use the API, the price is $0.0020 / 1K tokens, 1k tokens is approximately equal to 750 words, or 500 Chinese characters. New users of OpenAI will have a credit of $5 to be used during your first 3 months. Therefore, it is best not to share the API key with others. If the API key is leaked, you can delete it in the OpenAI background and generate a new one.

# Edit shortcut to replace API key

Open the "Shortcuts" app, find the downloaded "ChatGPT" shortcut, press and hold to select "Edit", and paste the above API key into the text box below.

<div align="center">
<img width="500" src="img/replace-api-key.png" />
</div>

# How to use it

Start the "shortcut" with Siri, just say "Hey, Siri, ChatGPT", and then you can start chatting with Siri, our Siri has become very smart, enjoy! 🎉

> update: I recommend you to change the default name because Siri cannot recognize "ChatGPT" accurately.

If you don't like the name, you can rename the shortcut, change it to any name you like, and then you can chat with Siri just say "Hey, Siri, xxx", xxx is the new name you  chose, it's better not to add special symbols to the name. It’s hard to read the symbols 😂, If Siri cannot match the name of the shortcut, it won’t work!

Of course, you can also directly click the shortcut to use. At this time, it is used in the form of a dialog box, and it will not be read out. You can add it to your Home Screen for quick access. end 🎉

# Advanced usage

This shortcut supports iPhone, iPad and Mac, supports continuous conversations, supports quit chat, new chat. The usage is as follows:

- The default is to support continuous dialogue, which can record context and discuss issues continuously.
- If you want to start a new chat, say "New chat" when it's our turn, Siri will start a new round of chat, which means that the previous context will be lost, and you can't continue chatting with the previous information.
- If you want to quit ChatGPT to use the system's Siri, you can say "Quit chat" on your turn. Of course, you can also close Siri directly and open it again. But here it is more natural to provide the command to exit.

## Customize name, icon and hint messages.

- img1: Rename and choose icon
- img2: Welcome and continue hints

| img1 | img2 |
| :-------------: |:-------------:|
| <img width="200" src="img/IMG_rename-icon.png" /> | <img width="200" src="img/IMG_welcome-continue.png" /> |

Customize hint messages.

- img1: Quit chat command, quit chat hint
- img2: New chat command, new chat welcome hint

| img1 | img2 |
| :-------------: |:-------------:|
| <img width="200" src="img/IMG_quit-chat.png" /> | <img width="200" src="img/IMG_new-chat.png" /> |

## Customize system message

You can also customize system message, which help set the behavior of the assistant. In this "shortcut" system message is one of the default system messages of ChatGPT used:

> You are ChatGPT, a large language model trained by OpenAI. Answer as concisely as possible. Knowledge cutoff: Sep 2021.

Modify method, edit the "shortcut", slide down, and find the position as shown in the figure:

<div align="center">
<img width="240" src="img/IMG_system-message.png" />
</div>

For example, you can replace system message with the following:

> I will let you act as a translator. Your goal is to translate any language into English. Please do not use an interpreter accent when translating, but to translate naturally, smoothly and authentically, using beautiful and elegant expressions.

Of course, you can also write it yourself, such as asking him to be a joker, a writer, a chef, etc. There are endless ways to play. You can also find a prompt written by someone else on the Internet, and fill it in here with a little modification. Here it is recommended to  duplicate the "shortcut" and give the cope one a different name. For example, the shortcut for translation is called "My Translator", so you can just say "Hey, Siri, My Translator", and start a ChatGPT dedicated to translation.

Also you can directly say what you want the ChatGPT to be when it's your turn to say. For example    ask him to help you as a translator. But it’s not as convenient as the “shortcut” above that specifically modifies the system message for translation. That “translator” can work directly, which is very nice! This is also the meaning of Prompt, you can customize the using scene first, and then use ChatGPT more efficiently. This is why there are so many awesome prompt tutorials on the Internet. We can build our own prompt suitable for us and let ChatGPT to be more powerful!

# AI Image

## 1.0

- [简体中文版](https://www.icloud.com/shortcuts/b37ad418e4ec4e6d9846baa7df34e6f9)
- [English Version](https://www.icloud.com/shortcuts/eda268ebbaa64a23bfadc53f7c13c307)

## 1.1

Automatically save images to the photo album. 

- [简体中文版](https://www.icloud.com/shortcuts/82865070e10f4e79a021064518f77ca9)
- [English Version](https://www.icloud.com/shortcuts/6f8299a858184900b7ab2a4dbf048623)

# Contact

- Discord: <a href="https://discord.gg/r28WhZUtK8" target="_blank">ChatGPT Siri</a>
- Twitter: <a href="https://twitter.com/YueYangDev" target="_blank">@YueYangDev</a>

# FAQ

👉 <a href="https://github.com/Yue-Yang/ChatGPT-Siri/discussions/30" target="_blank">Questions</a>

# Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Yue-Yang/ChatGPT-Siri&type=Date)](https://star-history.com/#Yue-Yang/ChatGPT-Siri&Date)
