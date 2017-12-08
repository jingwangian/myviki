
### Socket functions

1. socket function is defined as following:
``` C
int socket(int domain, int type, int protocol);
```

2. Bind socket to the specific network resource(address and port)
``` C
int bind(int socket, socketaddr *addr, int length);
```



### Using socket on server side
1. create a socket by using **socket** function
2. bind the socket by using **bind** function
3. start listen by using **listen** function
4. Accept the request connection by using **accept**, and get a new socket
5. Using the **send/recv** on new socket to communicate with the client.
6. Close socket by using **close** function


### Using socket on Client side 
1. create a socket
2. 



###reference:
1. https://www.ibm.com/support/knowledgecenter/en/ssw_i5_54/rzab6/xnonblock.htm
2. https://www.ibm.com/support/knowledgecenter/en/ssw_i5_54/rzab6/poll.htm
