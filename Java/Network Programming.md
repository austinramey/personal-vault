- To setup:
	- Put into try statement
	- ServerSocket class
	- arguments: port number
	- Within try statement:
		- Socket socket = severSocket.accept();

```
try(ServerSocket serverSocket = new ServerSocket(5000)) {
	Socket.socket = serverSocket.accept();
	System.out.println("Client Connected.");
	BufferedReader input = new BufferedReader(new 
			InputStreamReader(socket.getInputStream()));
	PrintWriter output = new PrintWriter(socket.getOutputStream(), true);
	while (true) {
		String echoString = input.readLine();
		if(echoString.equals("exit")) {
			break;
		}
		output.println("Echo from server: " + echoString);
	}
} catch (IOException e) {
	System.out.println(e.getMessage());
}
```
