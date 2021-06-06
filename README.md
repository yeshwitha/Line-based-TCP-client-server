# Line-based-TCP-client-server

Written code for two applications for both client and server.

client and Server operations:
Server need to handle one client at a time. If client connects to the server, then it sends a string (standard ASCII characters) which protocol it supports. If client accepts any of the protocol, it says "OK". and Client should read the string and calculate the result and respond back to server. Server reads this results and compares it with its own results, if they match the server says "Success", otherwise "failure". once the server has responded, it can close the connection and then it return to wait for the next client.
