#vagrant_snort
=============

SNORT Intrusion Detection System set up on a vagrant virtual machine. Ideal for quick home testing

##Overview
This runs Ubuntu12.04 LTS configured over a bridged network.

Snort is configureed to read it's configuration from the shared folder (TODO)
SNORT is configured to write it's logs to the shared folder (TODO)
I may add the visual tools (TODO)
 
##QuickStart.

Install VirtualBox
vagrant box add precise64 http://files.vagrantup.com/precise64.box
vagrant up

##References

Read the quick start here: http://docs-v1.vagrantup.com/v1/docs/getting-started/
List of available boxes here: http://www.vagrantbox.es/
Configure VmWare here: http://docs.vagrantup.com/v2/vmware/configuration.html
http://www.ripe.net/internet-coordination/press-centre/understanding-ip-addressing