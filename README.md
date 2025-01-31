# ☎ CallGPT
A dead simple way to call the ChatGPT API from your machine

## 👀 What is this?

This is a dead simple way to have a ChatGPT client that you have control over and that you can actually use without having to go to any website

- Its just 1 html ~300 lines HTML file that you can save on your desktop or anywhere else and have an interface where you can interact with ChatGPT.

- Except for loading jQuery and Bootstap from a CDN -- there are no services involved. You can download these 2 libraries on your local and work with that if you prefer.

- There are no 3rd party services called  -- the calls are made from your machine to OpenAI.

- The functinality is intentionally kept at a bare-minimum so you can tweak it to your liking.

- You will need to use an API key from OpenAI. The API is fairly cheap, but nevertheless a paid service.

<br/>


<img src="./image-v2.png" />


## 🤔 How to use:

1. Download this repo and save the HTML file on any location on your PC.

2. Double-click and run it using chrome.

3. Get an API key from OpenAI for ChatGPT ( from their website )

4. Put your API Key in the field in the top corner and make the calls.

5. Modify the HTML file as you like.

6. Enjoy! 🙂


## ⭐🤖🏃 Custom assistant:

There are 2 very simple examples of custom code examples shown of how you can have the bot execute some functions for you.

1. Change the background color of the page --> you can say "change background to red" and the background will change to red.
2. Change the text to white and it will change the text to white.


<video src='https://raw.githubusercontent.com/dminGod/CallGPT/main/callGPT.mov' />



To add more capabilities to the Bot:
- Write a new function that does what you want.
- In the bot initialization there is a list of commands that the bot can execute, the parameters it takes and when the function is called -- add your function to this list.
- There is a part of the response message parsing where we check if there are any commands sent by the bot for us to execute -- here we make the call to the function we made.

You can add stuff like calling the HackerNews API and showing it on the screen somewhere or call some local API to 
control the lights or toaster or whatever you want.





## 📝💪🏼 Write your own features:

1. Define the function that will do the work. For example:
<img src="custom_bot_v1.png" /> <br/>


2. Add a keyword that the bot can use to call this function

<img src="custom_bot_v2.png" /> <br/>

3. When you get a reply from the bot, see if any of your keywords is called, if yes, call your function:

<img src="custom_bot_v3.png" /> <br/>



## Tweak it to your liking:
<img src="./image-v3.png" />




