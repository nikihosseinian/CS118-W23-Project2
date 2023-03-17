# CS118 Project 2

This is the repo for Winter 2023 cs118 project  2 completed by Nikki Hosseinian and Zoya Haq. 

This project aims to create a custom reliable data transfer protocol similar to TCP but utilizing UDP in C/C++ programming language. By implementing this protocol in server and client applications, the project intends to improve the understanding of how TCP works, particularly in handling packet losses. Our project involves developing functions such as large file transmission with pipelining and loss recovery using Go-Back-N (GBN). 

## Installing and Running 
1. Clone the Repository: `git clone https://github.com/nikihosseinian/CS118-W23-Project2.git`
2. Change Directory: `cd CS118-W23-Project2`
3. Open 1st Terminal: 
<br /> Compile: `gcc server.c -o server`
<br /> Run: `./server <port> <ISN>`

          
4. Open 2nd Terminal 
    <br /> Compile: `gcc client.c -o client`
    <br /> Run: `./client <HOSTNAME-OR-IP> <PORT> <ISN> <FILENAME>`

         

## Academic Integrity Note

You are encouraged to host your code in private repositories on [GitHub](https://github.com/), [GitLab](https://gitlab.com), or other places.  At the same time, you are PROHIBITED to make your code for the class project public during the class or any time after the class.  If you do so, you will be violating academic honestly policy that you have signed, as well as the student code of conduct and be subject to serious sanctions.
