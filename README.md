## OPVN
    openvpn3 session-start --config ./something.ovpn
    openvpn3 session-manage --config ./something.ovpn --disconnect
    
## Terraform
    terraform destroy -target module.compartment_demo
