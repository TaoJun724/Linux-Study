.PHONY:all
all:server client

client:client.c comm.c
	gcc -o $@ $^
server:server.c comm.c
	gcc -o $@ $^

.PHONY:clean
clean:
	rm -rf client server
