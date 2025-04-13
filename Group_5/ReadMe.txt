===================================================================================================
--------------------------------How to use this--------------------------
===================================================================================================
1. Open 5 terminals
	-terminal 1 is for Server
	-terminal 2 is for peer1
	-terminal 3 is for peer2
	-terminal 4 is for peer3
	-terminal 5 is for Client
2. compile the three codes in each folder Server, peer1, peer2, peer3 and Client  
	 cpp server.c -o server  
	 cpp peer_node.c -o peerNode  
	 cpp peer_client.c -o peerClient  
3. run 
	/server <serverport>  
	/node <serveraddress> <serverport>  
	/node <serveraddress> <serverport>  
	/node <serveraddress> <serverport>  
	/client <serveraddress> <serverport>   
	server address is localhost here
4. The requested file should be with a peernode because The client will ask for a file name 
   and return the file if it is found with any node.
===================================================================================================
