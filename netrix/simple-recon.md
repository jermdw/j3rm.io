# simpleRecon

## Simple Local Network Stuff

### netDiscover ###

```netdiscover -p```

```netdiscover -i eth0 > localips.txt```

### Nmap

``` nmap -sP 192.168.1.0/24 ```

``` nmap -sP <IP address range>/<class subnet> | grep "report for" |        cut -d " " -f5 > nmapliveIPs.txt ```

