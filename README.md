# Impacket for Cyberplan

### Clone the repo, make sure you have root privileges (for smb port 445) and execute the following command 
```python3 -m venv ./venv && source ./venv/bin/activate && pip install pipx && python3 -m pipx install .```

### Example command: 
```ntlmrelayx.py -tf /tmp/testing/relay-list -smb2support -socks```

### This code is with a patch to filter for only admin sessions

### To uninstall:
```pipx uninstall impacket```