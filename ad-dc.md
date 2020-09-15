## Find out the name and IP of AD domain controller in your network

1. Open cmd prompt 

2. List all the LDAP and domain controllers.
> nslookup -a=all _ldap._tcp.dc._msdcs.example.com 

3. List all the Kerberos authentication servers.
> nslookup -a=all _kerberos._tcp.dc._msdcs.example.com 

4. List all the domain controllers using "nltest.exe"
> nltest /dclist:my-domain


