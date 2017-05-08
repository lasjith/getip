# GetIP
collecting the ip of the local machine and storing it to a file

## Change Log
04/05/2017
	ifconfig | grep "inet[^6]" | awk '{print $2}' | head -n1

### Version 1.0

