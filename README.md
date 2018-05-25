# client-server-lan-chat-basic<br>
The basic client-server model.<br>
Instructions to run:<br>
1. compile as follows:<br>
g++ foo.cpp -o foo -lws2_32 for both client and server.
2. Run the server.exe
3. Open powershell/cmd in the directory where these files are stored.
4. type in: ./foo_client localhost<br>
where foo_client is the name of the -o tag for client.Type localhost as it is.
5. At the client, send the password.
6. If server sends ok, communication begins. Else, resend password.
