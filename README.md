# efnetscan
 Basic network scanner tool based on ARP requests for Kali Linux made with python

# How to install and use
1) Download the main code
```
git clone https://github.com/K4hveci/efnetscan
```
2) Move the main code to ```/bin```
```
mv efnetscan /bin
```
3) To use, enter the range of IP with ```-r``` parameter.
```
efnetscan -r 192.168.0.0/24
```

Note: this tool uses scapy, if you encounter with a problem about scapy please try:
```
pip3 install scapy
```
