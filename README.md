# GetIP
collecting the ip of the local machine and storing it to a file

## Change Log
04/05/2017 
	curl ipecho.net |grep "Your IP" | awk '{print $4}' | awk -F "<" '{print $1}'

### Version 4.0

