Displays all active ports:

netstat -a
_________________________________________________________

Displays the executable file of a connection or listening port (requires administrator rights):

netstat -b
_________________________________________________________

Shows statistics about your network connection (received and sent data packets, etc.):

netstat -e
_________________________________________________________


Displays the fully qualified domain name (FQDN) of remote addresses:

netstat -f
_________________________________________________________


Brings up the netstat overview menu:

netstat -i
_________________________________________________________


Numerical display of addresses and port numbers:

netstat -n
_________________________________________________________


Displays the process identifier (PID) associated with each displayed connection:

netstat -o
_________________________________________________________


Displays the connections for the specified protocol, in this case TCP  (also possible: UDP, TCPv6, or UDPv6):

netstat -p TCP
_________________________________________________________


Lists all connections, all listening TCP ports, and all open TCP ports that are not listening:

netstat -q
_________________________________________________________


Displays the IP routing table:

netstat -r
_________________________________________________________


Retrieves statistics about the important network protocols such as TCP, IP, or UDP:

netstat -s
_________________________________________________________


Shows the download status (TCP download to relieve the main processor) of active connections:

netstat -t
_________________________________________________________


Informs about all connections, listeners, and shared endpoints for NetworkDirect:

netstat -x
_________________________________________________________


Displays which connection templates were used for the active TCP connections:

netstat -y
_________________________________________________________


Displays the respective statistics again after a selected number of seconds (here 10):

netstat -p 10
