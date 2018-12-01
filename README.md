# Welcome to sd92-sk github page!

## What I will find here?
I'd like to share scripts or other stuff that is useful to me and hopefully someone else.

For example when i create Debian linux VM, it's PITA to go over full install always and configure additional packages manually. Instead I make first install, then add packages, change settings in config files and then create template in hypervisor.

Even that is not good for me, because I want it to be consistent when new Debian release is out and wish to have clean install of that with my modifications. So I have script for that.

More examples are install scripts for LAMP, xmpp server or similiar.

I also want to automate gathering information from my XenServer/[xcp-ng](https://xcp-ng.org/) hypervisor which VMs are on which networks, and on my LAN network what are their MAC addresses, as I have MAC addresses statically mapped to IP addresses to be assigned by DHCP.

Reason for that is, I'm never sure which ones are free to use. I designated only ~30 IP's, but have about 20 VMs, with not sequentially assigned addresses - the lower the IP, the higher importance to me, higher ones are for testing stuff and to be deleted soon :D I think I'll create website which will display that info for me, and not do it via excel/calc.

### EOF
