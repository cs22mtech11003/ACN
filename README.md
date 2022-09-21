# ACN

# Socket Programming

## 1. Part A

a. Create a server (file server) program. It listens on a TCP socket. The
server is meant to send specific file(s) (.txt/.png/.pdf) to its client
depending on the file requested (file path).




## Screenshots

![App Screenshot](https://i.postimg.cc/JhsKWpdt/one.png)


b. Create a client program which interacts with the file server on TCP. Client
TCP connects to the file server to fetch a file given the file path in the
server. Assume that a valid client knows the ip address, port number of
the file server.

## Screenshots

![App Screenshot](https://i.postimg.cc/3x8Y9vft/two.png)
## 2. Part B

a. Extend the file server program in Part A to serve multiple clients in
parallel. i.e. if two different clients ask for a file, the server shall satisfy
both the clients in parallel without making any client wait. Maximum
number of clients to honor can be set at the server.
## Screenshot
1.
![App Screenshot](https://i.postimg.cc/3rGGQs8P/three.png)
2.
![App Screenshot](https://i.postimg.cc/htLM4JSR/four.png)
3.
![App Screenshot](https://i.postimg.cc/xjNZD1bn/five.png)
4.
![App Screenshot](https://i.postimg.cc/4NbBs74k/six.png)







b. Create one server program as per #a above and many instances of valid
clients mentioned in Part A and check the working of parallel file download
from the server. Check for all possible errors for which the server may give
error message/error code to the client. E.g., file doesn’t exist. Check the
situation when the server is busy serving other clients and one client has
to wait for the server to start serving it after serving other clients.


## Screenshot

![App Screenshot](https://i.postimg.cc/tJbWMkx1/seven.png)
##  Execution Steps

Execution Steps:

### PART A:

#### Server Side:

Gcc serverF.c -o server

./server  9898

#### Client Side:

gcc clientF.c -o client

./client 127.0.0.1 9898

### PART B:

#### Server Side:

Gcc serverFF.c -o server

./server  9898

#### Client Side:

gcc clientFF.c -o client

./client 127.0.0.1 9898
# Plagiarism Statement

I certify that this assignment/report is my own work, based on my personal study and/or
research and that I have acknowledged all material and sources used in its preparation, whether
they be books, articles, reports, lecture notes, and any other kind of document, electronic or
personal communication. I also certify that this assignment/report has not previously been
submitted for assessment in any other course, except where specific permission has been
granted from all course instructors involved, or at any other time in this course, and that I have
not copied in part or whole or otherwise plagiarized the work of other students and/or persons. I
pledge to uphold the principles of honesty and responsibility at CSE@IITH. In addition, I
understand my responsibility to report honor violations by other students if I become aware of it.

Name of the student : MEDHA RACHEL PANNA

Roll No : CS22MTECH11003
