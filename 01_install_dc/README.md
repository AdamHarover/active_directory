# 01 Installing the domain controller

1. use `sconfig` to:
	- change the host name
	- change the IP address to static
	- change the DNS server to our own IP address

2. Install the Adctive Directory Windows feature	

```shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```