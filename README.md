# Django-official-ChatGPT-linebot-Render
# 一個使用Django框架和GPT3.5 turbo/ChatGPT，創造linebot的專案，快速建置於平台Render。


<div align="center">
  <img src="demo/demo1.png" width="300"/>
</div>

<div align="center">
  <img src="demo/demo2.png" width="300"/>
</div>

### [English](https://github.com/pyfbsdk59/Django-official-ChatGPT-linebot-Render/blob/main/README_en.md)
### [日本語](https://github.com/pyfbsdk59/Django-official-ChatGPT-linebot-Render/blob/main/README_jp.md)



### 1. 本專案參考了以下前輩和官方的方案改成製作，只針對剛學習Python或Django的朋友來佈置linebot在Render上。Render可取代取消免費方案的Heroku，來測試Side Project。

https://github.com/howarder3/GPT-Linebot-python-flask-on-vercel<br><br>
https://github.com/vercel/examples/tree/main/python/django


### 2. 和Vercel版本的差別，注意Start Command要改為gunicorn config.wsgi:application來啟動。（一個坑）

<div align="center">
  <img src="demo/demo_g.png" width="600"/>
</div>


### 3. openai的依賴必須使用0.27.0以上版本。
------
### Line和openai api設置請參考： https://github.com/howarder3/GPT-Linebot-python-flask-on-vercel
