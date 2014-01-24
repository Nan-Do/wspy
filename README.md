wspy
====

wspy is a python wireless ids. It detects which clients are connected to a network. The tool can be used to dectect intruders in the network and to create the client usage patterns. That is when the clients usually connect to the network and for how long.
It comes with a c extension called wireless that manages and controls the wireless interface. In order to run requires root priveleges. Those privileges are required to put the card in monitor mode. It depends on scapy to run. After compiling the c extension please put the file wireless.so in the same directory as the rest of the python files. In order to run the aplication just run:
      python WSpyCurses.py
      
It will try to detect the wifi interface and do everything else automatically.
