# Mikrotik RouterOS API Bruteforce Tool
Note: this is a fork of https://github.com/mrhenrike/MikrotikAPI-BF with some fixes and improvements. Changes:
* bug fix for empty list response
* added retries on socket timeout when opening the connection
* added ability to autosave current progress and continue after program restart. Example: `python3 mikrotikapi-bf.py -t 192.168.0.1 -d /tmp/passwords.txt -a /tmp/autosave.json` 