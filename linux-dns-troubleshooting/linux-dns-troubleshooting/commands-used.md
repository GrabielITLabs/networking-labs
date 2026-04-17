# Commands Used

```bash
resolvectl status
cat /etc/resolv.conf
ping google.com
sudo nano /etc/hosts
hostname
sudo rm /etc/resolv.conf
sudo ln -s /run/systemd/resolve/stub-resolv.conf /etc/resolv.conf
sudo systemctl daemon-reload
sudo systemctl restart systemd-resolved
sudo resolvectl dns enp0s3 8.8.8.8 1.1.1.1
ping 8.8.8.8
ping google.com
