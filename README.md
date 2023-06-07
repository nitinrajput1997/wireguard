# wireguard

### Install wireguard tools:
```
sudo apt install wireguard-tools resolvconf
```
#### Move conf file to this location
```
/etc/wireguard/Nitin.conf
```
#### Run this commands to run wireguard
```
sudo wg-quick up Nitin
sudo wg-quick save Nitin
sudo wg-quick down Nitin

sudo systemctl enable wg-quick@Shubham
```
#### Check status
```
sudo wg show
```
