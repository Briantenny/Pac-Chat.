# Pac-Chat.
Encrypted chat room.
Pac chat is intended to provide a secure self server chat network,
which ensure no remote storage of data between parties, it uses AES
encryption for secured data transfer over public network.. This consist of
server and client servers, one of the client has to host the server but
both have to still use the client sever.
This chat send data through and encryption tunnel, where a key know
known by both parties is used to decrypt the data. Once the key is successful
added the chat goes live and a back and forward communication is establish,
and it stays on as long as the server stays up
 The key can be changed in the Pac.conf file:-


 [config]


#HOST - change this to public IP if you are using it over the internet
HOST = 127.0.0.1

#PORT - any unused port can be used. forward this port if you want to use it over internet
PORT = 777

#PASSWORD - any password
PASSWORD = password

#VIEW - to view the live chat on the server change this to 1
VIEW = 1

Here you can change even the port and ip's if one is using it over
the net, where you still need to forward the port in router configuration

          ****USAGE****
##########################################

	Pac-server.py USAGE

 	$ python Pac-server.py

##########################################



##########################################

  Pac_client.PY USAGE

  $ python Pac_client.py "host_ip" "port" "password" "nick_name"

##########################################
