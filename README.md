# Discord-QR-Scam
Discord Image Token Grabber 

### About
A Python script that automatically generates a Nitro scam QR code and grabs the Discord token when scanned. This tool demonstrates how people can trick others
into scanning their Discord login QR Code, and gain access to their account. Use for Educational Purposes only.

![img1](https://images-ext-2.discordapp.net/external/IaPERJO86kX1THyf7bxZCz9lHxhCliGdBQwv8sg1A0w/https/cdn.tesla.sexy/21bf42cd-7bae-4505-8bae-35da33d64ae9/0b6bd27086.png)


## Usage
1. If you dont have python installed, download python 3.7.6
and make sure you click on the 'ADD TO PATH' option during
the installation.

2. Install the required modules > ```pip install -r requirements.txt``` or double click `pip_install_requirements.bat`

3. Type ```python QR_Generator.py``` in cmd to run or double click `run_script.bat`

4. Wait for the `discord_gift.png` to be generated. Send the image to the victim and make them scan it.

5. QR Code only lasts about 2 minutes. Make sure you send a fresh one to the victim and he is ready to scan.

6. When the QR Code is scanned, you will automatically be logged in to their account and the script will grab the Discord token.

## Troubleshoot
Make sure your chromedriver.exe file is the same version as your current Chrome web browser version. To check your current Chrome version,
paste `chrome://settings/help` in Google Chrome.

if Chrome crashes,

1. Make sure your chromedriver.exe file is the same version as your Chrome web browser version
2. Download the latest version chromedriver.exe here: https://chromedriver.chromium.org/downloads
3. Then replace the chromedriver.exe file in the folder.

