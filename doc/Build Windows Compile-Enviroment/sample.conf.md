

##
## client.conf configuration file. Lines beginning with ## are comments.
##
 
# Network-related settings:

# Bind to given address and always listen on it. Use [host]:port notation for IPv6
#bind=<addr>

# Use as many addnode= settings as you like to connect to specific peers
#addnode=123.4.5.678

#addnode=123.4.5.678:12345

# Alternatively use as many connect= settings as you like to connect ONLY to specific peers
#connect=123.4.5.678.197

#connect=123.4.5.678:12345

# Listening mode, enabled by default except when 'connect' is being used
#listen=1

# Maximum number of inbound+outbound connections.
#maxconnections=

#
# JSON-RPC options (for controlling a running Client/Daemon process)
#

# server=1 tells YourClient-Qt and Daemon Mode to accept JSON-RPC commands
#server=0

# Bind to given address to listen for JSON-RPC connections. Use [host]:port notation for IPv6.
# This option can be specified multiple times (default: bind to all interfaces)
#rpcbind=<addr>

#  you must set rpcuser and rpcpassword to secure the JSON-RPC api. The first
# method(DEPRECATED) is to set this pair for the server and client:
#rpcuser=YOUR-USERNAME

#rpcpassword=Password?!


# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# By default, only RPC connections from localhost are allowed.!


# Specify as many rpcallowip= settings as you like to allow connections from other hosts,
#rpcallowip=


# NOTE: opening up the RPC port to hosts outside your local trusted network is NOT RECOMMENDED,
# because the rpcpassword is transmitted over the network unencrypted.

# server=1 tells Client-Qt to accept JSON-RPC commands.
# it is also read by the Dameon to determine if RPC should be enabled 
#rpcallowip=123.4.5.678/255.255.255.0

#rpcallowip=123.4.5.678

#rpcallowip=2001:db8:85a3:0:0:8a2e:370:7334/96


# Listen for RPC connections on this TCP port:
#rpcport=12345

# You can send commands to the GUI Version and Headless Daemon
# running on another host using this option:
#rpcconnect=127.0.0.1

# Create transactions that have enough fees so they are likely to begin confirmation within n blocks (default: 6).
# This setting is over-ridden by the -paytxfee option.
#txconfirmtarget=n

# Miscellaneous options

# Pre-generate this many public/private key pairs, so wallet backups will be valid for
# both prior transactions and several dozen future transactions.
#keypool=100

# Pay an optional transaction fee every time you send bitcoins.  Transactions with fees
# are more likely than free transactions to be included in generated blocks, so may
# be validated sooner.
#paytxfee=0.00


# User interface options

# Start minimized
#min=1

# Minimize to the system tray
#minimizetotray=1

