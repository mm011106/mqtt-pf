# mqtt-pf
init.d script for MQTT port forwarding 

usage: sudo /etc/init.d/mqtt-pf {start|stop}

Local port 22883 is forwarded to 1883 port of the remote host.
the key for encryption must be located in /etc/ssh.
/etc/ssh/ssh_config must contain the connection configuration for the host.

