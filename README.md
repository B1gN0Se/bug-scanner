## bug-scanner

Tested on **Kali Linux**  

Features: LFI, XSS, SQLI and Open Redirect.

Follow the commands below to run the scanner

**Run the installation commands as root**

```sh
git clone https://github.com/b1gn0se/bug-scanner
```
```sh
cd bug-scanner
```
```sh
pip3 install -r requirements.txt && wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb && dpkg -i google-chrome-stable_current_amd64.deb && rm google-chrome-stable_current_amd64.deb
```

**Run the python script as normal user**
```sh
python3 bug-scanner.py
```

**Note: To run the scanner correctly, always pass the URLs with empty parameters!**
