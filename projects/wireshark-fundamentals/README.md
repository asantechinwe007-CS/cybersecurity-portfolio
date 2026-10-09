 Wireshark Fundamentals: Traffic Analysis Notes

Goal

Build foundational skills for analysing network traffic safely and ethically.

What I learned

 A packet is a small unit of data travelling across a network.
 DNS translates website names into IP addresses.
 TCP provides reliable communication between devices.
 UDP is faster but does not guarantee delivery.
 TLS encrypts most modern web traffic.
 QUIC is a modern encrypted transport protocol commonly used by browsers.

 TCP flags

 SYN: starts a TCP connection.
 ACK: confirms received data.
 PSH: asks the receiving application to process data promptly.
 FIN: closes a TCP connection.

 Wireshark display filters


dns
tcp
tls
quic
tcp.port == 445

