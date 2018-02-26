# Pac-Chat.
## Encrypted chat room. 





![gnome-shell-screenshot-w7jldz](https://user-images.githubusercontent.com/20000608/35177361-a7eb92ea-fd8f-11e7-9ebb-58508000aed1.png)



Pac chat is a secure self server chat network,
which ensure no remote storage of data is retained. It uses an AES
encryption to secure data transfer over public network.. This consist of
server and client, on one end a server but
both have to still use the client script.
This chat sends data through an encryption tunnel, where a key
known by both parties is used to decrypt the message. Once the key is successfully
added, the chat goes live and communication is establish,
it stays on as long as the server stays up
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
