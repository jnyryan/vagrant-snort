#vagrant_snort
=============

Setup SNORT Intrusion Detection System on a vagrant virtual machine. Ideal for quick home testing.

##Overview

VagrantUP is a cool virtualization tech that uses VirtualBox to create a virtual machine. 
The VagrantFile instructs VagrantUp to download an Ubuntu image and run an install script on it.

This setup will:

- run Ubuntu12.04 LTS configured over a bridged network.
- Snort is configured to read it's configuration from the shared folder (TODO)
- SNORT is configured to write it's logs to the shared folder (TODO)
- I may add the visual tools (TODO)
 
##QuickStart.

- Install [VirtualBox](https://www.virtualbox.org/)
- Install [vagrantup](http://www.vagrantup.com/)
- Clone this repoitory
- Run 
```
  vagrant up
```

##References

Read the quick start here: http://docs-v1.vagrantup.com/v1/docs/getting-started/
List of available boxes here: http://www.vagrantbox.es/
Configure VmWare here: http://docs.vagrantup.com/v2/vmware/configuration.html
http://www.ripe.net/internet-coordination/press-centre/understanding-ip-addressing
