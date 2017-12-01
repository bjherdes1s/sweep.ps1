# sweep.ps1

This PowerShell Ping Sweep script is intended to allow for user specification of the IP range. 

This is ideal for any person dealing with a network larger than CIDR /24. If you are dealing with 
less hosts, sweep.ps1 will still fulfill your needs. 

Output of Data:
1. Successful/failed pings printed to console
2. Successfully pinged IPs will be stored in a file on your desktop called "success.txt"
3. Each IP that cannot be pinged will be printed to a file on your desktop called "failed.txt"

