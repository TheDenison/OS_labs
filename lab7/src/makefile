all: tcp udp

tcp: tcpserver.c tcpclient.c
	gcc tcpserver.c -o tcpserver
	gcc tcpclient.c -o tcpclient

udp: udpclient.c udpserver.c
	gcc udpserver.c -o udpserver
	gcc udpclient.c -o udpclient

clean:
	rm tcpserver tcpclient udpserver udpclient