# OralPen  
- **Slogan**：口语转书面，快用OralPen。
- **介绍**：录制语音转文字，借助 chatGPT 将口语提炼为书面用语。｜Audiopen 平替。
- **Introduction**: Record your voice and refine it into language ChatGPT understands.

## 准备工作

**如果你使用OpenAI 请注意：**
- 确保网络能正常访问 https://api.openai.com 域名
- 确保 API 帐户有足够余额：https://platform.openai.com/account/usage   

**如果你在国内不能访问 OpenAI，可以使用API2D。**

**API2D 特点：**
- 在国内可以正常访问，
- 功能和 OpenAI 完全一致
- 使用时只是密钥和API 网址不同
- 价格约为 OpenAI 官方 1.5 倍

详细内容，参见：[API2D](https://api2d.com/wiki/doc)

## 快捷指令下载
点击下面链接下载快捷指令，支持 iPhone、iPad、Mac、HomePod、CarPlay。
### V0.0.4
- [AI_语音笔记_V0.0.4](https://www.icloud.com/shortcuts/74bb4200b98e41fba0b4d7ec09fe755b)

#### **更新说明**
V0.0.4 
- 首次导入快捷指令会提示填写 API-key
- 调试版快捷指令增加转写内容评价
- 确定语音识别录制上限为 90秒，超出时长，快捷指令后自动弹出。且使用快捷指令时手机屏幕不能熄灭

### V0.0.3
- [AI语音笔记 V0.0.3](https://www.icloud.com/shortcuts/296d2cea617e4a77bc000d643c434df1)
#### **更新说明** 
- 修改提示语
- 未检测到内容时，不新建备忘录

### V0.0.2
- [AI语音笔记 V0.0.2](https://www.icloud.com/shortcuts/c7d148aeb7674840b1cd4c5bde2feb66)
#### **更新说明**
- 增加 OpenAI 第三方 API 服务
- 更新 promote，保证内容为中文输入
- 保证储存内容稳定性：即使chatGPT 联网失败也能保存愿语音内容

### V0.0.1 
- [AI语音笔记 V0.0.1](https://www.icloud.com/shortcuts/65de7f6e24064ca6afaade66cb1f360d)
#### **更新说明** 
- 完成最小功能，识别并保存语音

## 其他相关问题

- 如何安全使用API key（英文）：https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety  
- API keys: https://platform.openai.com/account/api-keys   
- API 用量: https://platform.openai.com/account/usage
- API 价格: https://openai.com/pricing 
- ChatGPT API 常见问题: https://help.openai.com/en/articles/7039783-chatgpt-api-faq    

## 使用方法
将快捷指令中的文本中【请在此替换自己的 OpenAI 的 API】内容删除，并替换为自己的API。


## 🙏感谢
- 灵感来自： AudioPen https://audiopen.ai/#! 
- 技术启发： https://github.com/Yue-Yang/ChatGPT-Siri  
