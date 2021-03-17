all: Client Server Server_async

Client:
	g++ -g -Wall daytime_client.cpp -o daytime_client -lpthread

Server:
	g++ -g -Wall daytime_server.cpp -o daytime_server -lpthread

Server_async:
	g++ -g -Wall daytime_server_async.cpp -o daytime_server_async -lpthread


clean: 
	rm daytime_client
	rm daytime_server
	rm daytime_server_async