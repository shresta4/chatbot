# chatbot
Twilio chatbot using Tensorflow.js

# local setup

Twilio is a serverless environment for Node.js code. 
The code in lyricsbot.js goes in a Twilio function. Check the box labeled 'Check for valid Twilio signature'. Go to [Active Numbers](https://www.twilio.com/console/phone-numbers/incoming) and select the # associated with this project. Configure an incoming message to direct to '/some_path' (being the path you assigned to the lyricsbot.js function) and default to https://demo.twilio.com/welcome/sms/reply/. 
\n\n Import @tensorflow/tfjs in [dependencies](https://www.twilio.com/console/functions/configure), and check 'Enable ACCOUNT_SID and AUTH_TOKEN'. 

# demo
Text +1 (202) 410 5495 and it will respond with lyrics based on your text! 