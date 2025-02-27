# <p align="center">CyberWaifu-Marai</p>
[中文](README.md "中文") [English](eng-README.md "English") [日本語](jp-README.md "日本語")

> ### This is a chatting Waifu program based on VITS & ChatGPT!

Effect demonstration BiliBIli:[《青春猪头少年不会梦见赛博女友》](https://www.bilibili.com/video/BV1rv4y1Q7eT "BiliBili")

**Functioning Now：**
* [x] Talking with ChatGPT
* [x] Convert AI's Response to wav file
* [x] Multi-Character voice generator
* [x] Voice Recognition
* [x] Connect to Marai Robort

**Under Construction：**
* [ ] Connect to Live2D


# Catalogue
* [1.Install Python venv：](#1.)
	* 1.1 [Enter directory with cd commend](#cd)
	* 1.2 [Create Python Venv:](#99)
	* 1.3 [Enter Python Venv:](#venv)
	* 1.4 [Install required library with Pip:](#pip)
* [2.Import pre-trained models to "model" folder（create a new one if doesn't exist):](#.model)
	* 2.1 [Double click model.exe to import Models](#cd1)
* [3.Run（Talk to your Waifu:](#22)
	* 3.1 [Get marai verify_key and QQ](#343533)
	* 3.2 [Get ChatGPT Token](#333)
	* 3.3 [Start chatting with CyberWaifu](#444)
* [4.known issue:](#9315)
* [5.Contributions:](#915)](#915)
## <span id="1.">1.Install Python Venv：</span>
> **Install Anaconda or Python>=3.7**
> 
> **This example name the venv：chatWaifu**

### <span id="cd">1.1 Enter project directory with cd command</span>
`cd YOUR_PROJECT_RESPORY`
![](readme/5.png)
### <span id="99">1.2 Create Python Venv:</span>

Conda:`conda create --name CyberWaifu python=3.10`
![](readme/1.png)
![](readme/2.png)

Python:`python -m venv chatWaifu`
![](readme/6.png)

### <span id="venv">1.3 Activate created venv:</span>
Conda:`conda activate chatWaifu`

![](readme/3.png)

Python:`.\chatWaifu\Scripts\activate.bat`
![](readme/7.png)

### <span id="pip">1.4 Install required library with Pip:</span>
`pip install -r requirement.txt`
![](readme/4.png)

## <span id=".model">2.import pre-trained models to root directory:</span>
Google Drive:https://drive.google.com/file/d/1tMCafhnUoL7FbevVQ44VQi-WznDjt23_/view?usp=sharing

Ali Drive: https://www.aliyundrive.com/s/9JEj1mp1ZRv 提取码: m2y3

### <span id="cd1">2.1Double click model.exe to import Models</span>

## <span id="22">3.RUN（Start chatting with CyberWaifu:</span>
Japanese Ver：`python ChatWaifuJP_marai.py`

Chinese Ver：`python ChatWaifuCN_marai.py`

### <span id="343533">3.1 Get marai verify_key and QQ</span>
#### At the beginning of the program is the configuration area shown below

#### ![](readme/8.png)

#### verify_key filling-in mirai-http-api set verifyKey

#### QQ fill in the use of the robot QQ

### <span id="333">3.2 Get ChatGPT Token</span>
#### Log in to ChatGPT whith link:https://chat.openai.com
#### Press F12 to enter command center
#### Find Application -> cookie -> __Secure-next-auth.session-token
#### Copy the value into cmd and press ENTER

### <span id="444">3.3 Start chatting with CyberWaifu</span>

Start talking when the console prompts "You:" and then the sentence is recorded and sent to the ChatGPT conversation. 

## <span id="9315">4.known issue:</span>

### Because of ChatGPT's restrictions, conversations from unregistered usrs are all in one session...

## <span id="915">5.Contribution：</span>
- [MoeGoe_GUI]https://github.com/CjangCjengh/MoeGoe_GUI
- [Pretrained models]https://github.com/CjangCjengh/TTSModels
- [PyChatGPT]https://github.com/terry3041/pyChatGPT
