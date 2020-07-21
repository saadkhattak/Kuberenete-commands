## Node Issues
kubectl get nodes -o wide
kubectl describe node nodename
Check the status of the Docker service:
sudo systemctl status docker
journalctl --unit docker
Start up and enable the Docker service, so it starts upon bootup:
