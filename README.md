A simple raw-socket packet sniffer that captures packets from a specified network interface and prints their summaries.
Dependencies:
• Python 3
• Scapy (pip install scapy)
Root privileges to access raw sockets
Usage : The target interface can be changed by opening the source code and changing the
'interface' variable

chmod +x PacketSniffer.py
python3 PacketSniffer.py

