#Remote Command Execution using UDP

SAMPLE OUTPUT:
-----------------
***Server side:***

> gcc server.c -o server

> ./server
```
Connected...
Command Received: date
 
Sat Oct 30 17:32:14 UTC 2021

Command Received: ls
 
client  client.c  main.term  server  server.c
```
![image](https://user-images.githubusercontent.com/91663578/139543317-b976e56c-5af3-45eb-a76a-892ad46133a6.png)

***Client side:***

> gcc client.c -o client

> ./client
```
Enter the Command to Execute: date

Command Sent!

Server: Command successfully received and executed!

Enter the Command to Execute: ls

Command Sent!

Server: Command successfully received and executed!
```
![image](https://user-images.githubusercontent.com/91663578/139543390-12a3927d-0507-493f-87fe-fcd2d66cfb9f.png)

<!--P.S. Software used: CoCalc Online Linux Terminal -->  
