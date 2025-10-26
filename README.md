# Go TCP Listener

This is a simple TCP server written in Go that listens on port 42069. When a client connects, the server reads data from the connection line by line and prints it to the console.

## Running the server

To run the server, use the following command:

```bash
go run ./cmd/tcplistener
```

## Testing the server

You can test the server by connecting to it with a TCP client like `netcat` or `telnet`.

In a separate terminal, run:

```bash
netcat localhost 42069
```

Then, type any message and press Enter. The message will appear in the server's console. To close the connection, press `Ctrl+D`.
