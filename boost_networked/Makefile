all: Client Server

Client:
	g++ -g -Wall daytime_client.cpp -o daytime_client -lpthread

Server:
	g++ -g -Wall daytime_server.cpp -o daytime_server -lpthread

clean: 
	rm daytime_client
	rm daytime_server