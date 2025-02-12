# 2/9/25 Notes

Virtual machines have ports, connectivity, IP address, basically every thing an physical computer has. VM servers are physical servers that host many VMs in them (This is what AWS/Cloud companies mostly use). Accessing the VM requires verification, not necessarily a password, a SSH key also works. 

A key works like this: You have a file with info (private key) and the server has a key as well (public key) (Acts like a key and lock). When logging on, the computer finds your key file and it sends to the server to compare to the public key, if it matches, a connection is allowed.
