KEYLOGGER
This repository contains a simple keylogger developed for educational purposes. The keylogger records keystrokes from a target machine and stores them in a local file. This tool is intended for security professionals and researchers to understand how keylogging techniques work and how to better secure systems against such attacks.

⚠️ Disclaimer: This keylogger is for educational and ethical research purposes only. Unauthorized use of this software against individuals or systems is illegal and unethical.
Features:
    Captures keystrokes and stores them in a log file
    Lightweight and easy to set up

Requirements:
    Python 3.x
    Required libraries: pynput

Installation
    Clone the repository: git clone https://github.com/yourusername/keylogger.git
													cd keylogger
    Install dependencies: pip install pynput
    Run the keylogger: python keylogger.py

Usage
    Running the keylogger: Once the script is started, it will log all keystrokes in a file (keylog.txt by default).
    Stopping the keylogger: Use keyboard interrupt (esc) in the terminal to stop it or terminate the process if running as a background service.

Notes
    This keylogger is not designed for malicious purposes. It is solely for educational purposes to illustrate potential vulnerabilities.
    Always get proper authorization before deploying any logging software on a device.

Legal Disclaimer
This software is provided solely for ethical research and security awareness. Any unauthorized access or use of keylogging software without consent is illegal. The developer does not endorse or support any malicious use of this tool and is not liable for any misuse.
