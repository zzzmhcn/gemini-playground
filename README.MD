# Gemini 2.0 Flash 游乐场

## 项目简介

只需准备一个Gemini API Key，即可一键部署一个Gemini多模态对话的网站.
使用Deno/Cloudflare免费无服务器部署，并且进行了API中转，不限地区/网络环境，打开即用。

## Deno部署（推荐）

1. [fork](https://github.com/tech-shrimp/gemini-playground/fork)本项目
2. 登录/注册 https://dash.deno.com/
3. 创建项目 https://dash.deno.com/new_project
4. 选择此项目，填写项目名字（请仔细填写项目名字，关系到自动分配的域名）
5. Entrypoint 填写 `src/deno_index.ts` 其他字段留空 
   <details>
   <summary>如图</summary>
   
   ![image](/docs/images/1.png)
   </details>
6. 点击 <b>Deploy Project</b>

## Cloudflare Worker 部署

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/tech-shrimp/gemini-playground)


## 使用方法

填入API Key, 点击Connect按钮即可对话。
以下三个按钮分别是：
- 启用麦克风
- 启用摄像头
- 分享屏幕
<br>
![image](/docs/images/2.png)

## 感谢：

网站UI： 
```
Author: ChrisKyle<br>
Project: https://github.com/ViaAnthroposBenevolentia/gemini-2-live-api-demo<br>
MIT License : https://github.com/ViaAnthroposBenevolentia/gemini-2-live-api-demo/blob/main/LICENSE
```

Gemini转成OpenAI格式： 
```
Author: PublicAffairs<br>
Project: https://github.com/PublicAffairs/openai-gemini<br>
MIT License : https://github.com/PublicAffairs/openai-gemini/blob/main/LICENSE
```