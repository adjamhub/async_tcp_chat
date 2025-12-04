# Async TCP Chat

Easy chat module for a TCP chat server or client

## peer mode

Run in peer with 2 instances chatting each other. Just call:

$ async_tcp_chat --peer 1

in the first peer and

$ async_tcp_chat --peer 2

in the second one.



## server-client mode

Run the server calling

$ async_tcp_chat --server

and then connect the clients you like just calling:

$ async_tcp_chat --client



## wx GUI mode

If you prefer, you can run the client in wx GUI mode.

$ async_tcp_chat --gui
