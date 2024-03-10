# IPSca-Reinforced

**Forked from cam-stalk, by vladiroPatron**

A modified version of IPSca designed to mitigate compatibility and connectivity issues.

## Note

- Much appreciation to cam-stalk, the original developer of this tool.
- Various enhancements made with care by vladiroPatron.
- Tested on MacOS and Linux; Windows compatibility not tested but should work with proper package installation.
- For support, contact me on Discord: @vladirocox

## About IPSca

- Universal bruteforcer for web interfaces of IoT devices, like Routers, IP-Cameras, etc.
- Embedded brute force function.
- User-friendly graphic interface.

## Usage

- `python3 main.py`
- Or, if you are experiencing crashes, run it as root:
- `sudo python3 main.py`

## Requirements

- `Python >= 3.6` - Installation Guide
- Python modules: `pip3 install -r requirements.txt`
- Masscan installed and added to `$PATH` variable (already embedded in the tool)

## Features

- Embedded Masscan (root required)
- Export options: json, csv, html (ipcam screenshots)
- Snapshot capturing from: `iCatch`, `Hipcam`, `Hikvision (App-Webs/)`, `GoAhead`, `Foscam`, `Netwave`, `Tenvis`, `D-Link`

## Crashing Fixes

# If your client crashes randomly during brute forcing or IP scanning, verify the following:

- There are no blank rows in the desired IP-Adress list, and also no IP-Adresses that aren't followed by their ports.
- If you are still experiencing crashes, try running the tool as root:
- `sudo python3 main.py`

## Disclaimer

- For educational use only
