# ssh
#taking remote control for the server.
#after making an instance and generating a key,
#first the path to the directory where the .pem file is saved,
#then,

* ls -l | grep delta.pem

* chmod 600 delta.pem

* ssh -i delta.pem ubuntu@publicDNS


#Using public DNS is the best practice,
#Name server are responsible for resolving the ip address
