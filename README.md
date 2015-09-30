## UNIX multiclient socket app

------

### what is this?
This is a lab work attempt on designing multiclient socket app for UNIX environment. This work 
circumvents traffic congestion problem which appear whenever we use single client mode. We 
worked on manipulating file descriptors for each incoming port requested by each clients. 
However, limitation of maximum number of clients highly depends on the memory of the system 
and the buffer size. 

### skeleton
This is already working solution. It will yield different result on different environment. 

### contribution
By changing socket setting to nonblocking, it is possible to design a multiclient socket app 
to imitate real-condition of socket application. Refer to line-by-line comments on `main.cpp` 
to get the idea of our work.

Execute `server` executable file to invoke the server side.

### contact
For any inquiry, contact me at yanuart.adityan[at]gmail.com

Thanks a lot!
