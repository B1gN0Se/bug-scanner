# Bug-Scanner

**Description**: Bug-Scanner is a powerful and versatile multi-vulnerability scanner designed to detect various web application vulnerabilities, including Local File Inclusion (LFI), Open Redirects (OR), SQL Injection (SQLi), Carriage Return Line Feed (CRLF), and Cross-Site Scripting (XSS).

## Features

- **LFI Scanner**: Detect Local File Inclusion vulnerabilities.
- **OR Scanner**: Identify Open Redirect vulnerabilities.
- **SQL Scanner**: Detect SQL Injection vulnerabilities.
- **XSS Scanner**: Identify Cross-Site Scripting vulnerabilities.
- **CRLF Scanner**: Identify CRLF vulnerabilities.
- **Multi-threaded scanning**: Improved performance through multi-threading.
- **Customizable payloads**: Adjust payloads to suit specific targets.
- **Success criteria**: Modify success detection criteria for specific use cases.
- **User-friendly command-line interface**: Simple and intuitive.
- **Save vulnerable URLs**: Option to save the results of vulnerable URLs to a file.
- **HTML Report Generation**: Generates a detailed HTML report of found vulnerabilities.

## Installation (as root)

```sh
python3 -m venv bug_setup
```
```sh
source bug_setup/bin/activate
```
```sh
git clone https://github.com/B1gN0Se/bug-scanner.git
```
```sh
cd bug-scanner
```
```sh
pip3 install -r requirements.txt
```
```sh
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```
```sh
dpkg -i google-chrome-stable_current_amd64.deb
```
```sh
apt install -f
```
```sh
rm google-chrome-stable_current_amd64.deb
```
## Run the tool as normal user - not root
```sh
python3 bug-scanner.py
```

## Input Information:

- **Input URL/File**: You can provide a single URL or an input file containing a list of URLs to scan.
- **Payload File**: Select or provide a custom payload file for the type of vulnerability you want to scan for.
- **Success Criteria:**:  Define the patterns or strings that indicate a successful exploitation attempt.
- **Concurrent Threads:**: Set the number of threads for multi-threaded scanning.
- **View and Save Results:**: Results will be displayed in real-time as the scan progresses.

After the scan completes, you will have the option to save the URLs found to be vulnerable to a file for future reference.

**NOTE: To run the scanner correctly, always pass the URLs with empty parameters!**
