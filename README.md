# Multithreaded-Online-Quiz-System 
Developed by Arjun Pratap Choudhary for Computer Networks Project
Computer Networks Project - Multi-threaded Online Quiz System, developed in C language based on TCP protocol, including development of one Main Server, three Sub-servers and unlimited clients.


## Instructions:

1) First Run "Main Server"
2) then run "Sub Servers"
3) after running all of 3 sub servers finally run "Client"
4) ENTER PROPER INPUT WITH CORRECT SPELLINGS..

#### Commands to compile:
```
gcc -std=c11 main_server.c -o main_server
gcc -std=c11 sub_server_1.c -o sub_server_1
gcc -std=c11 sub_server_2.c -o sub_server_2
gcc -std=c11 sub_server_3.c -o sub_server_3
gcc -std=c11 client.c -o client
```
#### Commands to run:
```
./main_server
./sub_server_1
./sub_server_2
./sub_server_3
./client
```
