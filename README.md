## bug-scanner

====================================================
**XSS not working for now, working on this**
====================================================

Features: LFI, XSS, SQLI and Open Redirect.

Follow the commands below to run the scanner

```sh
git clone https://github.com/b1gn0se/bug-scanner
```
```sh
cd bug-scanner
```
```sh
pip3 install -r requirements.txt && pip3 install prompt_toolkit && pip3 install selenium && pip3 install webdriver_manager
```
```sh
python3 xlsNinja.py
```

**Note: To run the scanner correctly, always pass the URLs with empty parameters!**
