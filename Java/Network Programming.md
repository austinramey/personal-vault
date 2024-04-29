- To setup:
	- Put into try statement
	- ServerSocket class
	- arguments: port number
	- Within try statement:
		- Socket socket = severSocket.accept();
`try(ServerSocket serverSocket = new ServerSocket(5000)) {Socket socket = serverSocket.accept()}`
