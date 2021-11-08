
Displays all active ports:

netstat -a


Displays the executable file of a connection or listening port (requires administrator rights):

netstat -b


Shows statistics about your network connection (received and sent data packets, etc.):

netstat -e


Displays the fully qualified domain name (FQDN) of remote addresses:

netstat -f


Brings up the netstat overview menu:

netstat -i


Numerical display of addresses and port numbers:

netstat -n


Displays the process identifier (PID) associated with each displayed connection:

netstat -o


Displays the connections for the specified protocol, in this case TCP  (also possible: UDP, TCPv6, or UDPv6):

netstat -p TCP


Lists all connections, all listening TCP ports, and all open TCP ports that are not listening:

netstat -q


Displays the IP routing table:

netstat -r


Retrieves statistics about the important network protocols such as TCP, IP, or UDP:

netstat -s


Shows the download status (TCP download to relieve the main processor) of active connections:

netstat -t


Informs about all connections, listeners, and shared endpoints for NetworkDirect:

netstat -x


Displays which connection templates were used for the active TCP connections:

netstat -y

 Displays the respective statistics again after a selected number of seconds (here 10):

netstat -p 10
