# batchresolve
This bash script uses nslookup to determine the FQDNs from a list of IP addresses.
Future development is to include:
1) The ability to pass a range of IPs through CIDR notation (e.g. batchresolve 192.168.0.0/16) 
   or defined range (e.g. batchresolve 192.168.0.4-12)
2) An option to save the output to a file.

USAGE:
batchresolve -i <file with list of IPs>
