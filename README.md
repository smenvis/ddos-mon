ddos-mon
========

A tool to monitor and mitigate various types of DoS and DDoS attacks

ddos-mon monitors networks for various types of DoS and DDoS attacks. If an
attack is detected an alert is sent to an admin and rules can be set to block
hosts that are engaging in any attack.

ddos-mon can detect a wide range of attacks from TCP/UDP floods and reflection
attacks, such as NTP and SNMP, to application-layer attacks such as recursive
GET flood attacks and SSL re-negotiation attacks. See the feature list for a
full list of attacks ddos-mon can detect and mitigate.

ddos-mon operates on a client-server model allowing for multiple clients to be
monitored and managed from a single server. The central server can be set to
periodically ping clients to ensure that the are still online and not under
active attack and are therefore unable to send an alert. In the event of an
attack, mitigation rules can be shared across clients reducing the likelihood
of an attack cascading and impacting other clients on the network.

Featutes
========

ddos-mon can detect the following types of DoS and DDoS attacks:

* NTP reflection attcks
* SNMP Reflection attacks
* Slowloris attacks
* Slow HTTP attacks
* Recursive GET request attacks
* SSL re-negotiation attacks
* SQL wildcard attacks
* SYN fllod attacks
* UDP flood attacks
* SMTP flood attacks

ddos-mon has the following features:

* Central server to manage multiple clients
* CLI to monitor and manage clients from central server
* Early warning system
* Send attack alerts
* Blcok IP addresses of attcking nodes
* Set time-limit for blocked IP addresses
* Share rules and attack intelligence across clients
* Encrypted communications between client and server

ddos-mon is still in early development and should not be relied upon for
security-critical applications at this time.

Additional features are planned for future releases of ddos-mon, such as a
web-based interface and the ability to optionally share anonymous attack
intelligence to other users of ddos-mon.

smenvis