# Qt test

## On linux
- sudo apt-get install build-essential
- sudo apt-get install qtcreator
- sudo apt-get install qt5-default
- sudo apt-get install qt5-doc
- sudo apt-get install qt5-doc-html qtbase5-doc-html
- sudo apt-get install qtbase5-examples
- sudo apt-get install libqt5websockets5-dev

- iptables -A PREROUTING -t nat -i eth3 -p tcp --dport 1234 -j DNAT --to-destination 192.168.57.25:80
- iptables -A FORWARD -p tcp -d 192.168.57.25 --dport 80 -j ACCEPT
- iptables -A POSTROUTING -t nat -s 192.168.57.25 -o eth3 -j MASQUERADE
- https://serverfault.com/questions/532569/how-to-do-port-forwarding-redirecting-on-debian