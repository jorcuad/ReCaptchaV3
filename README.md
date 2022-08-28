# ReCaptchaV3
reCAPTCHA is a free service from Google that helps protect websites from spam and abuse. A “CAPTCHA” is a turing test to tell human and bots apart. It is easy for humans to solve, but hard for “bots” and other malicious software to figure out.

reCAPTCHA v3 helps you detect abusive traffic on your website without user interaction. Instead of showing a CAPTCHA challenge, reCAPTCHA v3 returns a score so you can choose the most appropriate action for your website.

<p align="center">
 <a href="https://www.youtube.com/watch?v=tbvxFW4UJdU">
  <img width="90%" src="https://github.com/jorcuad/ReCaptchaV3/blob/main/images/yt-video.PNG">
 </a>
</p>

## Whats the demo about?

I'm checking how reCaptcha V3 works, what are the API endpoints and their responses. The demo is implemented in a [static web page desployed in Netlify](https://recaptchav3.croke.es/). In the webpage is explained how the messages are exchanged and the APIs called.

## Can I use this code?

Please don't use this code in production. This implementation is insecure. In order to simplify the demo, I'm using the public and private key in the frontend (There is no backend since is a jamstack app hosted in Netlify)

__The private key must be used in the backend, otherwise the reChapta result can be manipulated.__

## Disclaimer
I am not responsible for the use of this code or the effects it may have on the systems where it is used. If you use this code you agree that you are using it at your own risk.
