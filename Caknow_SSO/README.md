For that, open `/etc/hosts` and edits as follows:

````
##
# Host Database
#
# localhost is used to configure the loopback interface
# when the system is booting.  Do not change this entry.
##
127.0.0.1 localhost
255.255.255.255 broadcasthost
::1             localhost 
# ...
127.0.0.1 api.caknow.affiliate.com
127.0.0.1 api.caknow.affiliate2.com
127.0.0.1 server.com

server.com is used for login function, it can distribute the token and verify the token of SSO-Client"# Caknow"
