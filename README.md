# GetIP
## Collecting the public ip and storing it to a file
04/05/2017 
	curl ipecho.net |grep "Your IP" | awk '{print $4}' | awk -F "<" '{print $1}'
### Version 4.0

## Collecting the public ip and storing it to a file
04/05/2017
	curl ipecho.net/plain
### Version 3.0

## Collecting the local ip and storing it to a file
04/05/2017
	ifconfig | grep "inet[^6]" | awk '{print $2}' | head -n1
### Version 2.0

## Collecting the local ip and storing it to a file
04/05/2017 
	(hostname -I | awk '{ print $1 }')
### Version 1.0
