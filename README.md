# Network Packet Sniffer

A Python-based network packet sniffer built using Scapy. Developed as Task 1 of the CodeAlpha Cybersecurity Internship.

## Features
- Captures live network traffic
- Parses TCP, UDP, and ICMP packets
- Displays source/destination IPs and ports
- Extracts raw payloads
- Saves captured packets to a log file

## Requirements
- Python 3.x
- Scapy
- Npcap (Windows)

## Installation
pip install scapy

## output example
[16:04:18] [TCP] 192.168.29.218:61127 --> 104.208.16.89:443 | Payload: b'\x17\x03\x03...'

##  TOOLS USED
- Python
- Scapy
- Npcap
