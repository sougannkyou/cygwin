CC	= gcc

CFLAGS	= -Wall
CFLAGS	+= -g

#LIBS = lresolv -ldl  -lnsl -lsocket 
all:server client
server: server.c
	$(CC) $(CFLAGS) -o $@ $<

client: client.c
	$(CC) $(CFLAGS) -o $@ $<

clean:
	rm -rf *~ *.exe