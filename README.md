# Reliable-UDP-Transfer

A system implying reliable transfer of data between two PCs using UDP.
The application is coded in C language
Trasnfer takes place via sockets, sending 5 packets at a time with total size 500 bytes.
Each packet has a sequence number and ack is sent by the receiver for the packets received.
If ack is not received the packet is sent by the sender using selective repeat.
