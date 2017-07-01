# Man-Overboard-Bot
Will poll Twitter for the keywords defined in config.json. When the keyword matches, the bot retweets the relevant tweet. View it in action at http://www.Twitter.com/ManOverboardBot

[![Build Status](https://github.com/TrentPierce/Man-Overboard-Bot)

Donate
------------

If you're feeling kind, feel free to throw some cash my way for a beer!

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KRVLFLJB3PUF6">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif"/>
</a>

Disclaimer
------------

This bot is written purely for educational purposes. I hold no liability for what you do with this bot or what happens to you by using this bot. Abusing this bot *can* get you banned from Twitter, so make sure to read up on [proper usage](https://support.twitter.com/articles/76915-automation-rules-and-best-practices) of the Twitter API.

License
------------

You can fork this repository on GitHub as long as it links back to this original repository. Do not sell this script as I would like the code to remain free.

Prerequisites
------------

  * TwitterAPI
  * Python 2.7
  
Configuration
------------

Open up `config.json` and make the values correspond to your Twitter API credentials.

Installation
------------
From the command line:

	pip install TwitterAPI
	
Then run:

	python main.py
