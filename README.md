## OVPN
    openvpn3 session-start --config ./something.ovpn
    openvpn3 session-manage --config ./something.ovpn --disconnect
    
## Terraform
    terraform destroy -target module.compartment_demo
    
## Screen (Linux)
list screens:
	
    screen -ls

create screen session
    
    screen -S name

detach from a screen
    
    screen -d 
    ctrl+A+D
    > if you connected to the screen this will KILL IT if there's nothing running like and endless process

kill screen
    
    screen -SX name quit


attach to a screen
    
    screen -rx name
