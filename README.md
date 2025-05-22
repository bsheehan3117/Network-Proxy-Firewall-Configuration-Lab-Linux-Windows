# Network-Proxy-Firewall-Configuration-Lab-Linux-Windows

• Needed to securely route traffic from a Windows VM through a Linux host, controlling allowed protocols using a custom iptables-based firewall and verifying secure communication paths.

• Configured static IP addresses on both systems and edited BIND and netplan settings for name resolution.

• Created and tested iptables NAT and FORWARD rules on the Linux host to allow only DNS (UDP 53), HTTPS (TCP 443), and Webmin (TCP 10020) traffic.

• Verified proxy setup by running curl and ping commands from the Windows client to validate traffic behavior.

• Demonstrated HTTPS access and DNS resolution success while ICMP (ping) was correctly blocked.

• Ensured configurations persisted and were secure against unintended traffic.

• Successfully established a functioning secure network proxy with precise traffic filtering.

• Validated firewall enforcement using both command-line tools and real-time testing scenarios, confirming the correct isolation of services and protocols.
