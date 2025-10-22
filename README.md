**Description**

This project provides a backend solution that captures network traffic passing through a specified interface, enabling efficient and real-time analysis of network activity.

**Tech Stack**

Backend :  Python + SqlAlchemy

**Run**

1. Initialize the environment : `uv init`  
2. Create virtual environment : `uv venv`
3. Activate the virtual environment : `source .venv/bin/activate`
4. Install requirements.txt : `uv add greenlet scapy SQLAlchemy typing_extensions` 
5. Run as :
    `sudo $(which python) network_analyzer.py --interface <interface-name>`

**Note: <interface> : specify interface connected to internet**