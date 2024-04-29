- To setup:
	- Put into try statement
	- ServerSocket class
	- arguments: port number
	- Within try statement:
		- Socket socket = severSocket.accept();
# EchoServer Code
```
try(ServerSocket serverSocket = new ServerSocket(5000)) {
	while (true) {
		Socket.socket = serverSocket.accept();
		System.out.println("Client Connected.");
		BufferedReader input = new BufferedReader(new 
			InputStreamReader(socket.getInputStream()));
		PrintWriter output = new PrintWriter(socket.getOutputStream(), 
			true);
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
# EchoClient Code
```
try(Socket socket = new Socket("localhost", 5000)) {
	BufferedReader echoes = new BufferedReader(
		new InputStreamReader(socket.getInputStream()));
	PrintWriter stringToEcho = new 
		PrintWriter(socket.getOutputStream(), true);
	Scanner scanner = new Scanner(System.in);
	String echoString;
	String response;
	do {
		System.out.println("Enter string to be echoed: ");
		echoString = scanner.nextLine();
		stringToEcho.println(echoString);
		if(!echoString.equals("exit")) {
			response = echoes.readLine();
			System.out.println(response);
		}
	} while (!echoString.equals("exit"));
} catch (IOException e) {
	System.out.println(e.getMessage());
}
```
