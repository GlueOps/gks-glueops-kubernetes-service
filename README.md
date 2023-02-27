# gks-glueops-kubernetes-service


ansible -i inventory.ini all -u root -m ping
ansible-playbook -i inventory.ini bootstrap/bootstrap.yaml -u root



kubeadm init --apiserver-advertise-address "192.168.141.94" --control-plane-endpoint "<use-an-round-robin-dns-endpoint>" --pod-network-cidr "10.16.0.0/16" --service-cidr "10.17.0.0/16" --upload-certs



