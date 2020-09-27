# BridgeRelay

How we generate the template baseline for bridge relays, public is for public, private is for private 

Private directory will contain how we create the private bridge, deploy, and provide the details for connection.

# PublicBridge

Requirements:

Tor 

obfs4

How to install with Fedora as an example:

```
yum install tor obfs4 -y

```

As bridges use no identifiers the torrc found in the torrc directory of this repository will be suitable to deploy.



# What is a bridge?

Description provided by main Tor project page: https://2019.www.torproject.org/docs/bridges.html.en


 Bridge relays (or "bridges" for short) are Tor relays that aren't listed in the main Tor directory. Since there is no complete public list of them, even if your ISP is filtering connections to all the known Tor relays, they probably won't be able to block all the bridges. If you suspect your access to the Tor network is being blocked, you may want to use bridges.

The addition of bridges to Tor is a step forward in the blocking resistance race. It is perfectly possible that even if your ISP filters the Internet, you do not require a bridge to use Tor. So you should try to use Tor without bridges first, since it might work. 
