## Create new node on the network

```
ansible-playbook -i <MACHINE_IP>, node.yaml --extra-vars "network_name=<NETWORK_NAME> network_ip=<NETWORK_IP> inteface=<NETWORK_INTERFACE>"
```

## Install microk8s on all raspberry nodes 
```
ansible-playbook -i raspberrypis.yaml install_microk8s.yaml
```


