Usage
Installation
You will need to:

Install latest version of Google Chrome.
Install Python 3
Have a Facebook account without 2FA enabled

$ git clone https://github.com/king0fCode/get-facebook-friends.git
$ cd get-facebook-friends
# Set up a virtual env
$ python3 -m venv venv
$ source venv/bin/activate

# Install Python requirements

$ pip install -e .
The code is multi-platform and is tested on both Windows and Linux. The tool uses latest version of Chrome Web Driver. I have placed the webdriver along with the code but if that version doesn't work then replace the chrome web driver with the latest one according to your platform and your Google Chrome version.


How to Run
Fill your Facebook credentials into credentials.yaml
Edit the input.txt file and add many profiles links as you want in the following format with each link on a new line:
Make sure the link only contains the username or id number at the end and not any other stuff. Make sure its in the format mentioned above.
