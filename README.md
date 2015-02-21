# mqtt-pf
init.d script for MQTT port forwarding 

- usage: sudo /etc/init.d/mqtt-pf {start|stop}

```
Local port 22883 is forwarded to 1883 port of the remote host.
the key for encryption must be non-path-phrase.
ssh config file for the portforward connection should be prepared.
```

