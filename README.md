# MTProtoProxy Easy Installer
<h4>A bug free script to install MTProtoProxy on Centos or Ubuntu</h4>


# Why should we use this script?
1. Generate secret and port randomly
2. Automatic configuration of firewall server
3. The easiest proxy installer for Persian speakers
4. Supports Centos 7/8 or Ubuntu 18 or later and Debian 10 or later
5. Configure NTP automatically
6. Change port, TAG, secret, remove proxy, etc. after installing proxy

# Install the official script
<h3>Installing the script on the server</h3>

Run on your server
```
bash <(curl -Ls https://raw.githubusercontent.com/ach1992/Easy-Installer-MTProto-Proxy/main/Install.sh)
```
Because all the default values are considered, no other action is needed and you just have to wait until the proxy configuration is done on your server and after installing the script, see your proxy link.

<h4>How many people can connect to the proxy?</h4>

It can do over 10,000 on a modern CPU. cpu power will be shared between connected people. Do not generate more people than your CPU threads because your server may become unavailable.
For example, a server with a 2-core cpu can keep about 20,000 people connected!!!
##
Thanks to <a href="https://github.com/TelegramMessenger/MTProxy" target="_blank"> MTProxy Admin Bot </a> creator of the Proxy you can now install the proxy with a script.
