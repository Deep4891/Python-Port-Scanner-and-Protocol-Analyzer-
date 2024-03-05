Instructions:

The Python code below prompts the user to perform packet sniffing and port scanning. 

For packet sniffing:
1. The code scans for open interfaces and returns the available interfaces with their indeces. 
2. The prompt then asks the user to select the interface index number to perform packet sniffing. 
3. After that, the function scans for TCP and UDP packets.

For Port scanning: 
1. The function prompts the user to enter the target IP address
2. After that a prompt asks user to enter the port range to scan i.e. the start port and end port.
3. As a result, the code returns what ports are open or closed. 
4. If the code finds any open ports it then asks the user whether to close the open ports. If yes is responded then it successfully closes the open ports. 


Dependencies: 
Install socket library with command "pip install socket" in Windows terminal to connect to the network
Install psutil libary with command "pip install psutil" in the Windows terminal to scan the open interfaces
Install scapy library with command "pip install scapy" in the Windows terminal to scan the network packets
