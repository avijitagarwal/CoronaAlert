# CoronaAlert

This applicaton helps you check if you are in the vicinity of a Covid positive patient with the help of Distance Bounding Protocol. It uses the round trip time for the TCP signal to reach the Server (positive patient) and come back to the Client (you) as a measure to find the distance between the Covid positive patient and you.

The steps to use this application are:
For ServerSide part-
1. go to ServerSide folder.
2. Run command "javac *.java"
3. exit ServerSide folder
4. Run command "java ServerSide.Server"

For ClientSide part-
1. go to "ClientSide" folder
2. Run command "javac *.java"
3. Exit ClientSide folder
4. Run command "java ClientSide.Main"

It uses Java swing to help create a window based application where the Client can enter its IP address and get the distance to the Server.
