# AdaEchoServer
This project treats an echo server with Ada.
---
Create a network service on TCP port 12321, which accepts connections on this port and returns complete lines (using a carriage return/linefeed sequence as a line separator) to clients. 

No error handling is required. For the purposes of the test, it is only necessary to support connections from localhost (127.0.0.1 or perhaps ::1). 

It is recommended that the connection information is recorded on the standard output.

The implementation must be able to handle simultaneous connections from several clients. A multithreaded or multiprocess solution may be used. Each connection must be able to return more than one line.

The implementation must not stop responding to other clients if a client sends a partial line or stops reading responses.
