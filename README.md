# ipcat
**A very simple web service that return source IP address of request**
Normally used to create your own *showing me my IP* web service, which to answer **what is my IP?**

## Usage:
clone the source to your server which ip is $SERVER-IP and then run command:
    `./launch-web.sh &`

## Test:
From another computer run:
    `curl http://$SERVER-IP:8888`
