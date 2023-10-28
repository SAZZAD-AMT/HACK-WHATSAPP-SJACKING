
## Screenshot
![alt img](Screenshots/Screenshot1.png)
[Youtube Tutorial for installing and running it](https://www.youtube.com/watch?v=sYtH5-K2JZc)

## Prerequisites before installing:
1. Linux or MacOS. (Not working on windows)
2. Python 3.7+

1. Update Firefox browser to the latest version
2. Install the latest geckodriver from https://github.com/mozilla/geckodriver/releases and extract the file then do :
	* `chmod +x geckodriver`
	* `sudo mv -f geckodriver /usr/local/share/geckodriver`
	* `sudo ln -s /usr/local/share/geckodriver /usr/local/bin/geckodriver`
	* `sudo ln -s /usr/local/share/geckodriver /usr/bin/geckodriver`
3. Clone the repo with `git clone https://github.com/OWASP/QRLJacking` then do `cd QRLJacking/QRLJacker`
4. Install all the requirements with `pip install -r requirements.txt`
5. Now you can run the framework with `python3 QrlJacker.py --help`

## Tested on
- Ubuntu 18.04 Bionic Beaver
- Kali Linux 2018.x and up


