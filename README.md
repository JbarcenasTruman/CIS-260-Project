# CIS-260-Project: Cybersecurity Documentation
A Project for a Class For City Colleges of Chicago CIS 260 Class.

# Project Information
With the rise of malicious actors in the tech world, Being vigilant is key in monitoring our incoming and outgoing network traffic. 
In this project, I will be demonstrating how to monitor a network within a closed environment. Utilizing Cisco Packet Tracer to display the network flow between 3 computers. 2 will be connected via Ethernet to a modem, while one will be connected via WIFI. Seeing how data flows in packet tracer, the environment will be rebuilt inside a VM using Oracle. Utilizing Wireshark on the VM that will act as the Victim of the attack, spot and capture any malicious packets. Then by making sure they cant be leaked out or brought in to cause havoc in the network again, write up a cybersecurity report to prevent this affecting an office or business environment and implement steps for the next attack. 

# Setup and Scenario.
First, we build a network overlay inside Cisco packet tracer. Using a topology, we can show how a small office can have multiple different setups of devices and how they use their network for everyday tasks. The end devices will be 2 Pc nodes, one laptop node with Wi-Fi capabilities. The network itself will have one switch, one access point, and one router. Using an Oracle Virtual Box, Setup two PC VMs running Linux to show an example of an attack within the network. Utilizing a network branch inside the VirtualBox, I can show how a malicious actor has breached the network and connected to one inside the office space. By then Running a program that can mimic a packet being sent, i can send something to the network and into the PC of the office space and cause havoc. I then as someone who is investigating what is going on, use Wireshark to record what type of packet it is and then write up a report to prevent issues from happening again.


# Cyber Security Report
A Template for a Cybersecurity report will be used, as depending on each IT office and environment they will be different. This template has the basis of what most reports will look like and will be filled out as such. 


### Notes 9/26

Please look at [Zeek]
