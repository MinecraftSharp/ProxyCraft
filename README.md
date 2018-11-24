# ProxyCraft
Theory Paid Project

ProxyCraft is a super complex Minecraft-Aware proxy.

Servers over-rely on ScreenShares to look for active cheats. ProxyCraft acts as a MiddleMan "server" that connects you to a server.

ProxyCraft allows you to on-the-fly disconnect and connect with another computer, without disconnecting from the origin computer. This means that even when using blatant hacks, you can switch to a CLEAN MineCraft install and you will come away from the SS clean (assuming there are no hacks on that server). Servers using SS software, will not be able to detect ProxyCraft easily depending on the way ProxyCraft is configured.

# Getting started
## Download ProxyCraft from IcyWindSoftware.com
ProxyCraft is not free software due to it being a way of making hacks near undetectable

Only $5 USD per month

## Run and Install ProxyCraft
Once you have downloaded ProxyCraft, you will need to install it. Link your account to ProxyCraft and it will allow you to start the ProxyCraft server.

Warning: The ProxyCraft may add some latancy to the connection.

## Getting started with ProxyCraft
When you generate the ProxyCraft server, it will only allow one connection. Determine the localhost IP of the computer running ProxyCraft. You will need this to use ProxyCraft.

First we need to configure and test ProxyCraft before activating some more advanced features.

### Config the proxy
#### Default Mode (recommended)
In ProxyCraft, type in the IP or HostName, the port (default: 25565) and your minecraft credentials of the server you want to connect to.

Click start ProxyCraft connection

You can now connect to the ProxyCraft server

#### No-Cred mode (beta)
In ProxyCraft, type in the IP or HostName and the Port. Check No-Cred mode (beta) and connect to the.

Click start ProxyCraft connection

You can now connect to the ProxyCraft server

Note: This mode reads log files and uses the sessionToken found

#### InGame mode (beta)
In ProxyCraft select InGame mode.

Click start ProxyCraft connection.

Connect to the ProxyCraft server.
ProxyCraft will prompt you for a server and an IP

You will need to enter these

ProxyCraft will also prompt for a username and password or ask if it can scan for the sessionToken

#### Inject mode (beta)
ProxyCraft injects a dll into the running Minecraft Instance and uses the Minecraft Instance as the proxy.

This is tested should work with VAPE

### Ensuring ProxyCraft works
Open a Chest. Put items into this chest. We will use this to confirm that ProxyCraft has transferred the connection correctly. You can actually open any inventory other than the player inventory.

Connect to the ProxyCraft server from another computer. On the computer you were just on you should see a kick message of

ProxyCraft: Forwarding connection to <IP>
  
Note: DO NOT ENABLE RECONNECT OR AUTO CONNECT AS THAT WILL DISCONNECT THE NEW PROXYCRAFT SERVER

On the computer you just connected to, you should see the inventory

If you connect in the exact same state (with the inventory open), ProxyCraft has transfered the connection properly. We can go make ProxyCraft harder to detect.

## Hiding ProxyCraft
### Simple hiding (easy to detect)
* Make sure you add the server to your server list
* Dirrect Connect to ProxyCraft

### Host hiding (easy to detect)
* Edit the host file to forward connections from that server to the ProxyCraft server instead.

### DNS hiding (near impossible to detect)
Note: You will need BetterProxyCraft ($7 /month or 70 /year) to use this

ProxyCraft will create a new DNS server which you can use to connect to the server.

NOTE: This only works with servers that have a hostname (ex. mc.hypixel.net works but 532.197.261.195 will not work)

Change the dns settings on your computer or router to use the ProxyCraft DNS server.

This means that on the computer connected to ProxyCraft, you enter the HostName as if you were connecting to it normally.

Note: BetterProxyCraft uses Google DNS

Once connected, disable the Proxy and clear the DNS Cache
