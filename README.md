# Twitch-Unfollower
[![GitHub stars](https://img.shields.io/github/stars/TobiasPankner/Twitch-Unfollower.svg?style=social&label=Star)](https://GitHub.com/TobiasPankner/Twitch-Unfollower/stargazers/)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3TU2XDBK2JFU4&source=url)

- [Prerequisites](#prerequisites)
- [Getting your twitch authorization](#getting-your-twitch-authorization)
- [Run the script](#run-the-script)

Python script to mass unfollow twitch channels.  
Since websites that used to do the same don't work anymore, I created this simple Web Automation program to quickly unfollow alot of channels.

![readme_gif](https://user-images.githubusercontent.com/38639895/186439523-6339e09c-5453-4ed7-b29f-56b03456dde4.gif)


## Prerequisites  
  
 - Python3 ([Download](https://www.python.org/downloads/)) 

## Getting your twitch authorization
**Treat these headers like your password!**

1. Log into your Twitch account
2. Open Chrome dev tools (F12) -> Network
3. Refresh the page
4. Copy the cookie of one of the gql requests (Right click -> Copy -> Copy request headers)

## Run the script

 1. Install dependencies:   ```pip install -r requirements.txt```
 2.  [Get your twitch authorization](#getting-your-twitch-authorization)
 3. Create a file called "headers.txt" and paste the headers in there
 4. Run [unfollower.py](unfollower.py): `python unfollower.py`
