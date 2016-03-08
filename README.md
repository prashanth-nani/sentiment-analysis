---Snapdeal Review Grabber---

Features:
* Option to choose a proxy connection
* Works with authenticated proxy
* Fetches all the reviews of ALL the mobile phones available
* Record logs to capture errors
* Manages directories by itself (Automatic cleaning up of files when execution starts)
* Well documented with comments



Requirements:
* Python 3.4+
* Python modules:
	- bs4
	- requests
	- os
	- re


	
To install the requirements run these commands in the same order:
* sudo apt-get install python3
* sudo apt-get install python3-pip
* sudo pip3 install bs4
* sudo pip3 install requests
* sudo pip3 install os   (This may be already present by default)
* sudo pip3 install re


How to run?
1st method:
* ./snapdeal.py (By default uses python3.5)
2nd method:
* python3 snapdeal.py (Uses any python 3+ version available)


Github link: https://github.com/prashanth-nani/snapdeal-review-grabber
