# OperatingSystems

## Digital Album

This system consists in 3 main components: clients, servers, and gateway. 

The architecture between clients and servers/gateway is client-server.
The communications between servers are based in a peer to peer architecture.

This system implements a digital album. The client connects to the gateway that gives the ip of an available server. Then, the client can communicate with the server, to upload, download, remove, and give tags/hashtags to the photos.

The communications are done using TCP and UDP protocols implemeted in C, and a specific API was developed for this service.

This project was developed for the Operating Systems course, by [Pedro Mendes](https://github.com/pedrogbmendes) and [Miguel Pinho](https://github.com/miguelpinho), and had a final grade of 18.5/20.
