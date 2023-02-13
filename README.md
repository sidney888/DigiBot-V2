# DigiBot-V2
Auto-Checkout bot created for Shopify. 

# Bot Capabilities
Currently, this bot is able to find the recently loaded products on a shopify site, around the past 30 loaded products, be able to add to cart and checkout using post and get request. 
You are able to add some modifications such as monitor delay and add to cart delays. This is encouraged to avoid burning out proxies and being blocked by the site.

# Installation Instructions
1. Install a version of python 3.6 and above here: https://www.python.org/downloads/. Ensure that the correct version of python is installed using the following command:
```
python -version
```
2. Create a folder to hold this project repository and download the above files to this folder.
3. Locate the the file called config.json, this is where all the info to run the bot will be stored. 
4. Use any text editor you have, and fill each empty input in the config.json file with your information. (This info is kept private and will be stored locally on your computer).

# Running the Bot
1. Ensure that the correct information is added in config.json and delays are adjusted properly.
2. Open up the terminal, and locate to the folder that contains the file names "main.py"
3. Once in the folder, simply type in the following command to start the bot:
```
python main.py
```
4. The bot should be now running in your command line.


# Tasks to Get Done
1. Add a captcha solving window so that checkouts with captcha will be able to checkout using the bot. This is what I am working on currently. (The files in the project named captcha are just files that are not working as of now). I don't want to use selenium for the captcha harvester so I need to learn some GUI stuff for python to achieve this.
