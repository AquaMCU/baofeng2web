# What is it? .... and why?
Hello Ham Radio fans!

Since years I think of a project that would be so so cool to have and would massively improve the time I could spend talking to you on the air. 

What would that be you ask: A small and cheap radio that I control via my PC using a web UI !!!

How cool would that be. Whenever I want to talk to my friends, instead of going into my ham shack, I can just open my PC and .... voila. Not 
to mention, that I can get away with much less installation effort and a shorter antenna wire.

# Please Help!
It took me such a long time to start this because I really have no time for this. So I will try to provide a basic working setup. But to make this 
project a success, it needs some more love! I hope you will help me out.

What is needed:
* Improve this howto and documentation (Perhaps with pictures, Links to Info, Links to Hardware [BTW where can I buy an Easy Digi in Germany?], a youtube tutorial or similar? )
* Improve code ( Make the UI look nice. Clen the code. Document the code. Bugfix and improve the code)
* Write addons ( Include an optional recorder, interface a logbook, add on/off relais for radio, MQTT interface, ... )
* Help other people
* ...

So please just be creative and send a pull request.

Thank you and 73
DO2OA

# Installation
1. sudo install docker-compose
2. clone archive
3. sudo docker-compose up
4. Open browser ( http://<YOUR-IP>:7373/ )
5. Enjoy !!!

# Hardware
You need to wire up your baufeg with your raspberry pi

1. https://gist.github.com/tymarbut/d802e43ab306b4b9f2ba
2. Using Easy Digi

# Architecture
 WEB UI [VUE.js]
 - - - - Websocket
 nodjs
 - - - - 
 Hardware

# Functions
1st Functions
* PTT button on web
* Pipe audio from Baufeng to sound card
* Easy install using docker-compose
