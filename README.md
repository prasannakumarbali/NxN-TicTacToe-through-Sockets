
# The-NXN-TicTacToe-through-sockets-in-C
A mini project on client server architecture that lets you to play a Dynamic TicTacToe flawlessly



## Introduction
The-NXN-TicTacToe-through-sockets-in-C is a command-line based implementation of the classic Tic Tac Toe game using sockets in the C programming language. The game allows two players to connect to a server using sockets and play Tic Tac Toe on an N x N grid. This README file provides an overview of the project, instructions for compiling and running the code, and other relevant information. To Know more about the project refer the "ProjectReport" pdf

## Multi-Threading
The code utilizes multithreading to handle multiple clients concurrently. Each client connection is handled in a separate thread, allowing two players to play the game simultaneously.

## Prerequisites
To compile and run the code, you need to have the following prerequisites installed on your Linux system:

GCC (GNU Compiler Collection): A C compiler.

Sockets library: The code requires the standard sockets library available on Linux.
## Summary
Socket programming is a way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, while other socket reaches out to the other to form a connection. Server forms the listener socket while client reaches out to the server.
Protocol:TCP Variables:socket_id,bind_id,choice of client and server. Methods:socket(),bind(),listen(),accept(),connect(),send(),recv(),check_board()[To check the who won client or server],board().
Structure:sockaddr_in for setting the ip family,address,portno.
## Contact Details
Ekank - ekank1410@gmail.com

Krishna - krishnakumar.211it034@nitk.edu.in

Prasanna Kumar - baliprasanna@gmail.com



