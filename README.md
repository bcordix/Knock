# Windows port knocking client

A simple Windows port knocking client (UDP or TCP only).

For example to send UDP packets to 192.168.0.1 on the port 123, 456 then 789 :

```
knock.exe UDP 192.168.0.1 123 456 789
```

For example to send TCP packets to 192.168.0.1 on the port 123, 456 then 789 :

```
knock.exe TCP 192.168.0.1 123 456 789
```

For example to send TCP packets to example.com on the port 123, 456 then 789 :

```
knock.exe TCP example.com 123 456 789
```

License
----

Apache License
